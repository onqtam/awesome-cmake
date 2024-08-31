# Awesome CMake [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[<img src="https://rawgit.com/onqtam/awesome-cmake/master/cmake-logo.svg" align="right" width="100">](https://cmake.org/)

> A curated list of awesome [CMake](https://cmake.org/) scripts, modules, examples and others

Your contributions are highly welcome (first see [CONTRIBUTING.md](CONTRIBUTING.md)).

There is another file [`NonModernCMake.md`](NonModernCMake.md) with other links worth taking a look, but they use obsolete practices which are considered non-modern - like not using `target_*`-based dependency management - see [`#16`](https://github.com/onqtam/awesome-cmake/issues/16) and [`#42`](https://github.com/onqtam/awesome-cmake/pull/42) for more details.

## Contents

- [Community](#community)
- [Resources](#resources)
- [Package Management / Build Systems](#package-management--build-systems)
- [Modules](#modules)
- [Utility Scripts](#utility-scripts)
- [Toolchains](#toolchains)
- [Examples / Templates](#examples--templates)
- [Other](#other)

## Community

* [```#cmake``` on Freenode](http://webchat.freenode.net/?channels=cmake)
* [```/r/cmake``` on Reddit](https://www.reddit.com/r/cmake/)
* [```/r/cpp``` on Reddit](https://www.reddit.com/r/cpp/)
* [Official Discourse Forum](https://discourse.cmake.org/)
* [Stack Overflow](http://stackoverflow.com/questions/tagged/cmake)

## Resources

* [Latest Documentation](https://cmake.org/cmake/help/latest/)
* [FAQ](https://gitlab.kitware.com/cmake/community/-/wikis/FAQ)
* [Wiki](https://gitlab.kitware.com/cmake/community/-/wikis/home)
* [Webinars](https://cmake.org/webinars/)
* [Web Book](https://github.com/ruslo/CGold) - CGold: The Hitchhiker’s [Guide](https://cgold.readthedocs.io) to the CMake. [```[BSD2]```][BSD-2-Clause]
* [Modern CMake](https://github.com/toeb/moderncmake) - Modern CMake **PDF** and samples by the creator of [cmakepp](https://github.com/toeb/cmakepp). [```[MIT]```][MIT]
* [Tutorial](https://www.siliceum.com/en/blog/post/cmake_01_cmake-basics) - Modern CMake tutorials part1: CMake basics
* [Article](http://foonathan.net/blog/2016/03/03/cmake-install.html) - Easily supporting CMake install and find_package().
* [Article](http://foonathan.net/blog/2016/07/07/cmake-dependency-handling.html) - Easy dependency management for C++ with CMake and Git.
* [Article](https://steveire.wordpress.com/2016/08/09/opt-in-header-only-libraries-with-cmake/) - Opt-in header-only libraries with CMake.
* [Article](https://rix0r.nl/blog/2015/08/13/cmake-guide/) - Ultimate Guide to Modern CMake.
* [Article](https://web.archive.org/web/20190116071957/http://voices.canonical.com/jussi.pakkanen/2013/03/26/a-list-of-common-cmake-antipatterns/) - A list of common CMake antipatterns (from 2013 but still relevant).
* [Article](http://preshing.com/20170511/how-to-build-a-cmake-based-project/) - How to Build a CMake-Based Project.
* [Article](http://preshing.com/20170522/learn-cmakes-scripting-language-in-15-minutes/) - Learn CMake's Scripting Language in 15 Minutes.
* [Article](http://aosabook.org/en/cmake.html) - The architecture of CMake.
* [Lecture](https://www.youtube.com/watch?v=bsXLMQ6WgIk) - Effective CMake - by Daniel Pfeifer, C++Now 2017.
* [Article](https://devblogs.nvidia.com/parallelforall/building-cuda-applications-cmake/) - Building Cross-Platform CUDA Applications with CMake.
* [Tutorial](https://github.com/Wigner-GPU-Lab/Teaching/tree/master/CMake) - A step-by-step guide for understanding CMake.
* [Article + Lecture](https://steveire.wordpress.com/2017/11/05/embracing-modern-cmake/) - Embracing Modern CMake - by Stephen Kelly.
* [Lecture](https://www.youtube.com/watch?v=eC9-iRN2b04) - Modern CMake for Modular Design - by Mathieu Ropert, CppCon 2017.
* [Article](https://pabloariasal.github.io/2018/02/19/its-time-to-do-cmake-right/) - It's Time To Do CMake Right (one of the best articles about CMake).
* Articles - A series on CMake - by Martin Hořeňovský
    * [Basic CMake usage](https://codingnest.com/basic-cmake/).
    * [Basic CMake, part 2: libraries](https://codingnest.com/basic-cmake-part-2/).
* [Lecture](https://www.youtube.com/watch?v=jt3meXdP-QI) - Introduction to CMake - by Florent Castelli, C++ Sweden 2018.
* [Article](http://bastian.rieck.me/blog/posts/2018/cmake_tips/) - Some nice and accurate CMake tips.
* [Article](http://unclejimbo.github.io/2018/06/08/Modern-CMake-for-Library-Developers/) - Modern CMake for Library Developers.
* [Article](https://gist.github.com/mbinna/c61dbb39bca0e4fb7d1f73b0d66a4fd1) - Effective Modern CMake: a great summary of most good practices - by Manuel Binna.
* [Book](https://crascit.com/professional-cmake/) - Professional CMake: A Practical Guide (paid).
* [Book](https://leanpub.com/effective-cmake) - Effective CMake: Practical Advice to Write Better CMake (not fully written yet).
* [Web Book](https://cliutils.gitlab.io/modern-cmake/) - An Introduction to Modern CMake.
* [YouTube Series](https://vector-of-bool.github.io/2018/08/12/cmake-good.html) - How to CMake Good. [```[CC0-1.0]```][CC0-1.0]
* [Lecture](https://www.youtube.com/watch?v=y7ndUhdQuU8) - More Modern CMake ([slides & examples](https://github.com/Bagira80/More-Modern-CMake))- by Deniz Bahadir, Meeting C++ 2018.
* [Lecture](https://www.youtube.com/watch?v=y9kSr5enrSk) - Oh No! More Modern CMake ([slides](https://github.com/Bagira80/More-Modern-CMake/raw/master/OhNoMoreModernCMake.pdf))- by Deniz Bahadir, Meeting C++ 2019.
* [Article](https://cristianadam.eu/20190223/modifying-the-default-cmake-build-types/) - Modifying the default CMake build types/flags, toolchains and patches - Oh my! - by Cristian Adam.
* [Tutorial](https://github.com/schweitzer/modern-cmake-tutorial) - Tutorial and Example on How to Properly Use Modern CMake.

## Package Management / Build Systems

* [hunter](https://github.com/ruslo/hunter) - Cross-platform package manager for C++ (based on CMake ExternalProject). [```[BSD2]```][BSD-2-Clause]
* [cget](https://github.com/pfultz2/cget) - CMake package retrieval. This can be used to download and install CMake packages. [```[BOOST]```][BOOST]
* [cppan](https://cppan.org/) - C++ Archive Network - C++ Package Manager based on CMake, implemented in C++14. [```[APACHE2]```][APACHE2]
* [cpm](https://github.com/iauns/cpm) - C++ Package Manager based on CMake and Git. [```[MIT]```][MIT]
* [conan](https://github.com/conan-io/conan) - Conan C++ Package Manager, implemented in Python and has a CMake integration backend. [```[MIT]```][MIT]
* [fips](https://github.com/floooh/fips) - High-level build system/dependency management for distributed, multi-platform C/C++ projects. [```[MIT]```][MIT]
* [Ninja](https://github.com/ninja-build/ninja) - Build system that differs from others in two major respects: it is designed to have its input files generated by a higher-level build system (like CMake), and it is designed to run builds as fast as possible. [```[APACHE2]```][APACHE2]
* [vcpkg](https://github.com/Microsoft/vcpkg) - A tool to acquire and build C++ open source libraries. Uses CMake internally as a build script language. [```[MIT]```][MIT]
* [pmm](https://github.com/AnotherFoxGuy/pmm) - PMM is a module for CMake that manages... package managers. [```[MIT]```][MIT]
* [cpm](https://github.com/TheLartians/CPM) - A setup-free CMake + git dependency manager. [```[MIT]```][MIT]

## Modules

* [cmake-modules](https://github.com/rpavlik/cmake-modules) - [Ryan Pavlik](https://github.com/rpavlik)'s collection of CMake modules. There are a number of find modules, especially for virtual reality and physical simulation, some utility modules, and some patches or workarounds for CMake itself. [```[BOOST]```][BOOST]
* [cmake-modules](https://github.com/bilke/cmake-modules) - This is a collection of additional CMake modules. Most of them are from Ryan Pavlik. [```[BOOST]```][BOOST]
* [CMake](https://github.com/Eyescale/CMake) - [Eyescale](https://github.com/Eyescale)'s common CMake modules. [```[BSD3]```][BSD-3-Clause]
* [cmake-modules](https://github.com/jedbrown/cmake-modules) - CMake modules for some scientific libraries. [```[BSD2]```][BSD-2-Clause]
* [cgcmake](https://github.com/chadmv/cgcmake) - CMake modules for common applications related to computer graphics. [```[MIT]```][MIT]
* [FindMathematica](https://github.com/sakra/FindMathematica) - CMake module for Mathematica. [```[MIT]```][MIT]
* [extra-cmake-modules](https://github.com/KDE/extra-cmake-modules) - [KDE](https://github.com/KDE)'s extra modules and scripts for CMake. [```[BSD3]```][BSD-3-Clause]
* [FindICU.cmake](https://github.com/julp/FindICU.cmake) - CMake module to find International Components for Unicode (ICU) Library. [```[BSD2]```][BSD-2-Clause]
* [FindTBB](https://github.com/justusc/FindTBB) - CMake find module for Intel Threading Building Blocks. [```[MIT]```][MIT]
* [FindWiX](https://github.com/apriorit/FindWiX) - CMake module for building [Windows Installer](https://en.wikipedia.org/wiki/Windows_Installer) packages with [WiX toolset](http://wixtoolset.org). [```[BSD3]```][BSD-3-Clause]
* [FindIDL](https://github.com/apriorit/FindIDL) - CMake module for building [IDL](https://docs.microsoft.com/en-us/windows/win32/midl/interface-definition-idl-file) files with MIDL and generating CLR DLL using [Tlbimp](https://docs.microsoft.com/en-us/dotnet/framework/tools/tlbimp-exe-type-library-importer). [```[MIT]```][MIT]
* [cmake-modules](https://github.com/hanjianwei/cmake-modules) - [hanjianwei](https://github.com/hanjianwei)'s CMake module collection. [```[MIT]```][MIT]
* [YCM](https://github.com/robotology/ycm) - Extra CMake Modules for [Yet Another Robot Platform](https://github.com/robotology/yarp) and friends. [```[BSD3]```][BSD-3-Clause]
* [CMakeCM](https://github.com/AnotherFoxGuy/CMakeCM) - CMake Community Modules. ```[NO LICENSE]```
* [Metabench](https://github.com/ldionne/metabench) - CMake module for compile-time microbenchmarks. [```[BOOST]```][BOOST]
* [Oranges](https://github.com/benthevining/Oranges) - [Ben Vining](https://github.com/benthevining)'s library of CMake modules and toolchains [```[GPL]```][GPL]

## Utility Scripts

These provide a wide range of functionality - from dealing with compiler flags to using tools. Some also contain modules.

* [cotire](https://github.com/sakra/cotire) - Cotire (compile time reducer) is a CMake module that speeds up the build process of CMake based build systems by fully automating techniques as precompiled headers and unity builds for C and C++. [```[MIT]```][MIT]
* [ucm](https://github.com/onqtam/ucm) - For managing compiler/linker flags, collecting sources, precompiled headers, unity builds and others. [```[MIT]```][MIT]
* [cmakepp](https://github.com/toeb/cmakepp) - Enhancement Suite for the CMake Build System. [```[MIT]```][MIT]
* [sugar](https://github.com/ruslo/sugar) - CMake tools and examples: collecting source files, warnings suppression, etc. [```[BSD2]```][BSD-2-Clause]
* [DownloadProject](https://github.com/Crascit/DownloadProject) - CMake module for downloading an external project's source at configure time. [```[MIT]```][MIT]
* [buildem](https://github.com/janelia-flyem/buildem) - Modular CMake-based system that leverages ExternalProject to simplify builds. [```[LICENSE]```](https://github.com/janelia-flyem/buildem/blob/master/LICENSE.txt)
* [coveralls-cmake](https://github.com/JoakimSoderberg/coveralls-cmake) - Coveralls JSON coverage generator and uploader for CMake. [```[MIT]```][MIT]
* [compatibility](https://github.com/foonathan/compatibility) - Improved version of cmake-compile-features. [```[LICENSE]```](https://github.com/foonathan/compatibility/blob/master/LICENSE)
* [cmake-modules](https://github.com/Tronic/cmake-modules) - LibFindMacros development repository and other cool CMake stuff. [```[LICENSE]```](https://github.com/Tronic/cmake-modules/blob/master/LibFindMacros.cmake#L2)
* [GreatCMakeCookOff](https://github.com/UCL/GreatCMakeCookOff) - This is a repository of useful and less than useful CMake recipes. [```[MIT]```][MIT]
* [cppcheck-target-cmake](https://github.com/polysquare/cppcheck-target-cmake) - Per-target CPPCheck for CMake. [```[MIT]```][MIT]
* [clang-tidy-target-cmake](https://github.com/polysquare/clang-tidy-target-cmake) - Add clang-tidy checks to a target using CMake. [```[MIT]```][MIT]
* [cmake-unit](https://github.com/polysquare/cmake-unit) - Unit testing framework for CMake. [```[MIT]```][MIT]
* [cmake-header-language](https://github.com/polysquare/cmake-header-language) - CMake macro to determine the language of a header file. [```[MIT]```][MIT]
* [tooling-cmake-util](https://github.com/polysquare/tooling-cmake-util) - Utility and common library for all polysquare CMake tools. [```[MIT]```][MIT]
* [iwyu-target-cmake](https://github.com/polysquare/iwyu-target-cmake) - CMake integration for include-what-you-use. [```[MIT]```][MIT]
* [sanitizers-cmake](https://github.com/arsenm/sanitizers-cmake) - CMake module to enable sanitizers for binary targets. [```[MIT]```][MIT]
* [cmake-precompiled-header](https://github.com/larsch/cmake-precompiled-header) - Visual Studio and GCC precompiled header macro. [```[LICENSE]```](https://github.com/larsch/cmake-precompiled-header/blob/master/PrecompiledHeader.cmake#L31)
* [CMakePCHCompiler](https://github.com/nanoant/CMakePCHCompiler) - CMake precompiled headers via custom compiler extension - with reuse support! [```[MIT]```][MIT]
* [CMake-codecov](https://github.com/RWTH-ELP/CMake-codecov) - Enables code coverage and generates coverage reports with CMake targets. [```[GPL]```][GPL]
* [cmake-get](https://github.com/pfultz2/cmake-get) - Get dependencies in config or script mode. ```[NO LICENSE]```
* [ixm](https://github.com/slurps-mad-rips/ixm) - Make CMake less painful when trying to write Modern Flexible CMake.  [```[MIT]```][MIT]
* [CMakeCooking](https://github.com/hakuch/CMakeCooking) - Flexible development environments for CMake projects with external dependencies
. [```[APACHE2]```][APACHE2]

## Toolchains

* [dockcross](https://github.com/dockcross/dockcross) - Cross compiling toolchains in Docker images. [```[MIT]```][MIT]
* [android-cmake](https://github.com/taka-no-me/android-cmake) - CMake toolchain file and other scripts for the Android NDK. [```[BSD3]```][BSD-3-Clause]
* [ios-cmake](https://github.com/cristeab/ios-cmake) - Toolchain file and examples using CMake for iOS development. [```[BSD3]```][BSD-3-Clause]
* [qt-android-cmake](https://github.com/LaurentGomila/qt-android-cmake) - For building and deploying Qt based apps on Android without QtCreator. [```[LICENSE]```](https://github.com/LaurentGomila/qt-android-cmake/blob/master/license.txt)
* [mingw-w64-cmake](https://github.com/lachs0r/mingw-w64-cmake) - CMake-based MinGW-w64 Cross Toolchain - to build Windows binaries of mpv. [```[ISC]```][ISC]
* [cmake-avr](https://github.com/mkleemann/cmake-avr) - CMake toolchain for AVR. [```[LICENSE]```](https://github.com/mkleemann/cmake-avr/blob/master/LICENSE)
* [arduino-cmake](https://github.com/francoiscampbell/arduino-cmake) - This is the CMake project settings for the Arduino platform. [```[MPL]```][MPL]
* [polly](https://github.com/ruslo/polly) - Collection of CMake toolchain files and scripts for cross-platform build and CI testing. [```[BSD2]```][BSD-2-Clause]
* [toolchains](https://github.com/mosra/toolchains) - For cross-compiling with CMake. They are meant to be mainly used on ArchLinux. ```[NO LICENSE]```
* [cmake](https://github.com/staticlibs/cmake/tree/master/toolchains) - Collection of CMake toolchain files, mostly for static linking. [```[APACHE2]```][APACHE2]
* [Arduino-CMake-Toolchain](https://github.com/a9183756-gh/Arduino-CMake-Toolchain) - CMake toolchain for all official and 3rd party Arduino platforms. [```[MIT]```][MIT]

## Examples / Templates

* [cmake-init](https://github.com/cginternals/cmake-init) - Template for reliable, cross-platform C++ project setup using CMake. [```[LICENSE]```](https://github.com/cginternals/cmake-init/blob/master/LICENSE)
* [android-cmake](https://github.com/forexample/android-cmake) - Examples of using [ruslo/hunter](https://github.com/ruslo/hunter) package manager for an Android application. [```[BSD2]```][BSD-2-Clause]
* [hunter-simple](https://github.com/forexample/hunter-simple) - Example of downloading/installing dependencies using [ruslo/hunter](https://github.com/ruslo/hunter) package manager. [```[BSD2]```][BSD-2-Clause]
* [package-example](https://github.com/forexample/package-example) - Config mode of find_package (examples for [this](http://stackoverflow.com/questions/20746936/cmake-of-what-use-is-find-package-if-you-need-to-specify-cmake-module-path-an) Stack Overflow question). ```[NO LICENSE]```
* [minimal_cmake_example](https://github.com/krux02/minimal_cmake_example) - Minimal CMake example, that covers dependencies and packaging. [```[CC0-1.0]```][CC0-1.0]
* [cmake-example](https://github.com/bast/cmake-example) - Example project which demonstrates various CMake features. [```[BSD3]```][BSD-3-Clause]
* [cmake-examples](https://github.com/ttroy50/cmake-examples) - Useful CMake examples in a tutorial format. [```[MIT]```][MIT]
* [mini-cmake-qt](https://github.com/euler0/mini-cmake-qt) - Minimal CMake template for Qt 5 projects. [```[LICENSE]```](https://github.com/euler0/mini-cmake-qt/blob/master/LICENSE)
* [BASIS](https://github.com/cmake-basis/BASIS) - CMake [BASIS](https://cmake-basis.github.io) makes it easy to create sharable software and libraries that work together. [```[BSD2]```][BSD-2-Clause]
* [cpp-boilerplate](https://github.com/Lectem/cpp-boilerplate) - Template that aims to be a reference for modern CMake and CI. [```[MIT]```][MIT]
* [how-to-export-cpp-library](https://github.com/robotology/how-to-export-cpp-library) - An OS-agnostic template project for exporting either shared, static or header-only C++ library, sporting ctest and CI support, written in plain CMake with line-by-line tutorial comments. [```[MIT]```][MIT]
* [modern-cmake-sample](https://github.com/pabloariasal/modern-cmake-sample) - Best practices and proper usage of CMake by using targets. ```[NO LICENSE]```
* [CMakeInstallExample](https://github.com/DeveloperPaul123/CMakeInstallExample) - Installation example for a C++ project (Windows) with Cmake. ```[NO LICENSE]```
* [cpp14-project-template](https://github.com/arnavb/cpp14-project-template) - A C++14 template with CI, tests, code coverage, docs and static analysis integration. [```[CC0-1.0]```][CC0-1.0]
* [cmake_templates](https://github.com/acdemiralp/cmake_templates) - Templates for creating C++ libraries and executables (including conan). ```[NO LICENSE]```
* [cmake_snippets](https://github.com/adishavit/cmake_snippets) - Short copy-pasteable CMake snippets. [```[BSD3]```][BSD-3-Clause]
* [cmake-cookbook](https://github.com/dev-cafe/cmake-cookbook) - A huge CMake cookbook full of recipes. [```[MIT]```][MIT]
* [cpp-template](https://github.com/joshpeterson/cpp-template) - A template C++ repository, using CMake and Catch. ```[NO LICENSE]```
* [pitchfork](https://github.com/vector-of-bool/pitchfork) - A set of conventions for native C and C++ projects. [```[MIT]```][MIT]
* [cmake-examples](https://github.com/pr0g/cmake-examples) - A collection of as simple as possible, modern CMake projects. [```[MIT]```][MIT]
* [cpp-project](https://github.com/bsamseth/cpp-project) - Boiler plate for C++ projects - tests, CI, coverage, docs. [```[UNLICENSE]```][UNLICENSE]
* [ModernCppStarter](https://github.com/TheLartians/ModernCppStarter) - A template for modern C++ projects using CMake, CI, code coverage, clang-format, reproducible dependency management, tests using [doctest](https://github.com/onqtam/doctest) and much more. [```[UNLICENSE]```][UNLICENSE]
* [SeeMake](https://github.com/MhmRhm/SeeMake) - A feature-packed, ready-to-use CMake template with testing, static and dynamic checks, coverage reports, and more. [```[MIT]```][MIT]

## Other

* [autocmake](https://github.com/coderefinery/autocmake) - Using a autocmake.yml file [Autocmake](http://autocmake.readthedocs.io/en/latest/) composes CMake building blocks into a CMake project and generates CMakeLists.txt as well as a setup script, which serves as a front-end to CMakeLists.txt. [```[BSD3]```][BSD-3-Clause]
* [UseLATEX](https://gitlab.kitware.com/kmorel/UseLATEX) - Collection of CMake macros to simplify building LaTeX files. [```[BSD3]```][BSD-3-Clause]
* [scikit-build](https://github.com/scikit-build/scikit-build) - Improved build system generator for CPython C extensions. [```[MIT]```][MIT]
* [node-cmake](https://github.com/cjntaylor/node-cmake) - CMake-based build system for node.js native modules. [```[ISC]```][ISC]
* [cmake-font-lock](https://github.com/Lindydancer/cmake-font-lock) - Advanced syntax coloring support for CMake scripts inside Emacs. [```[GPL]```][GPL]
* [autovala](https://github.com/rastersoft/autovala) - Program that automatically generates CMake configuration files for your Vala project. [```[GPL]```][GPL]
* [catkin](https://github.com/ros/catkin) - CMake-based build system that is used to build all packages in Robot Operating System (ROS). [```[BSD3]```][BSD-3-Clause]
* [suitesparse-metis-for-windows](https://github.com/jlblancoc/suitesparse-metis-for-windows) - CMake scripts for painless usage of SuiteSparse+METIS. [```[BSD3]```][BSD-3-Clause]
* [osg-3rdparty-cmake](https://github.com/bjornblissing/osg-3rdparty-cmake) - CMake scripts for building OpenSceneGraph third party libraries. ```[MIXED LICENSE]```
* [cmake-d](https://github.com/dcarp/cmake-d) - CMake for D2. [```[MIT]```][MIT]
* [cmakeprojectmanager2](https://github.com/h4tr3d/cmakeprojectmanager2) - Enhanced CMake Project Manager plugin for Qt Creator. ```[NO LICENSE]```
* [cmake-lint](https://github.com/richq/cmake-lint) - Check for coding style issues in CMake files. cmakelint requires Python. [```[APACHE2]```][APACHE2]
* [git-cmake-format](https://github.com/kbenzie/git-cmake-format) - Integrate clang-format into your CMake project hosted in a git repository. [```[LICENSE]```](https://github.com/kbenzie/git-cmake-format/blob/master/license.txt)
* [configure-cmake](https://github.com/nemequ/configure-cmake) - configure-cmake is an autotools-style configure script for CMake-based projects. [```[CC0-1.0]```][CC0-1.0]
* [cmake-ast](https://github.com/polysquare/cmake-ast) - Python module to reduce a CMake file to an AST. [```[MIT]```][MIT]
* [cmake-checks-cache](https://github.com/cristianadam/cmake-checks-cache) - CMake checks cache helper modules. [```[MIT]```][MIT]
* [cmake_check](https://github.com/DaelDe/cmake_check) - Static analysis (linter) for the CMake language (e.g. to enforce modern CMake rules). [```[MIT]```][MIT]
* [cmake-language-server](https://github.com/regen100/cmake-language-server) - CMake Language Server Protocol Implementation. [```[MIT]```][MIT]
* [cmake-maven-plugin](https://github.com/cmake-maven-project/cmake-maven-project) - CMake integration for Maven builds. [```[APACHE2]```][APACHE2]
* [version-from-git](https://github.com/MhmRhm/version-from-git) - Bake git information into your binary. [```[MIT]```][MIT]

## License

This is released under the [**```Creative Commons Attribution 4.0 International```**](http://creativecommons.org/licenses/by/4.0/) License ```(CC BY 4.0)```.

[ISC]: https://opensource.org/licenses/ISC
[GPL]: https://www.gnu.org/licenses/gpl-3.0.html
[GPL2]: https://www.gnu.org/licenses/old-licenses/gpl-2.0.html
[LGPL]: https://www.gnu.org/licenses/lgpl-3.0.en.html
[MIT]: https://opensource.org/licenses/MIT
[BOOST]: http://www.boost.org/LICENSE_1_0.txt
[BSD-2-Clause]: https://opensource.org/licenses/BSD-2-Clause
[BSD-3-Clause]: https://opensource.org/licenses/BSD-3-Clause
[APACHE2]: http://www.apache.org/licenses/LICENSE-2.0
[CC0-1.0]: https://creativecommons.org/publicdomain/zero/1.0/
[MPL]: https://www.mozilla.org/en-US/MPL/2.0/
[UNLICENSE]: https://unlicense.org/
