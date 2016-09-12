# Awesome CMake [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome [CMake](https://cmake.org/) scripts, modules, examples and others.

This is released under the ```Creative Commons Attribution 4.0 International``` License ```(CC BY 4.0)```.

Your contributions are highly welcome (first see [CONTRIBUTING.md](CONTRIBUTING.md)).

For more awesome lists, see [awesome](https://github.com/sindresorhus/awesome).

# Contents

- [Articles](#articles)
- [Package Management](#package-management)
- [Modules](#modules)
- [Utility Scripts](#utility-scripts)
- [Toolchains](#toolchains)
- [Tutorials/Examples/Templates](#tutorialsexamplestemplates)
- [Other](#other)

## Articles

* [ruslo/CGold](https://github.com/ruslo/CGold) - The Hitchhiker’s [Guide](https://cgold.readthedocs.io) to the CMake. [BSD2][BSD-2-Clause]
* [Article](https://foonathan.github.io/blog/2016/07/07/cmake-dependency-handling.html) - Easy dependency management for C++ with CMake and Git.
* [Article](https://steveire.wordpress.com/2016/08/09/opt-in-header-only-libraries-with-cmake/) - Opt-in header-only libraries with CMake.
* [Modern CMake](https://github.com/toeb/moderncmake) Modern CMake PDF and samples by creator of [cmakepp](https://github.com/toeb/cmakepp). [MIT][MIT]
* [Ultimate Guide to Modern CMake](https://rix0r.nl/blog/2015/08/13/cmake-guide/) 
* [Older Modern CMake](https://meetingcpp.com/index.php/talkview13/items/13.html) Modern CMake for C++.
* [Article](http://voices.canonical.com/jussi.pakkanen/2013/03/26/a-list-of-common-cmake-antipatterns/) - A list of common CMake antipatterns (from 2013 but still relevant).

## Package Management

* [ruslo/hunter](https://github.com/ruslo/hunter) - Cross-platform package manager for C++ (based on CMake ExternalProject). [BSD2][BSD-2-Clause]
* [pfultz2/cget](https://github.com/pfultz2/cget) - CMake package retrieval. This can be used to download and install CMake packages. [BOOST][BOOST]
* [iauns/cpm](https://github.com/iauns/cpm) - A C++ Package Manager based on CMake and Git. [MIT][MIT]
* [conan-io/conan](https://github.com/conan-io/conan) - Conan C++ Package Manager, implemented in Python and has a CMake integration backend. [MIT][MIT]
* [floooh/fips](https://github.com/floooh/fips) - High-level build system/dependency management for distributed, multi-platform C/C++ projects. [MIT][MIT]

## Modules

* [rpavlik/cmake-modules](https://github.com/rpavlik/cmake-modules) - A collection of CMake modules. There are a number of find modules, especially for virtual reality and physical simulation, some utility modules, and some patches or workarounds for CMake itself. [BOOST][BOOST]
* [bilke/cmake-modules](https://github.com/bilke/cmake-modules) - This is a collection of additional CMake modules. Most of them are from Ryan Pavlik. [BOOST][BOOST]
* [Eyescale/CMake](https://github.com/Eyescale/CMake) - Common CMake modules. [BSD3][BSD-3-Clause]
* [tcbrindle/sdl2-cmake-scripts](https://github.com/tcbrindle/sdl2-cmake-scripts) - CMake scripts for finding the SDL2, SDL2_image and SDL2_ttf libraries and headers. [BSD2][BSD-2-Clause]
* [nerdvegas/vfxcmake](https://github.com/nerdvegas/vfxcmake) - CMake Find modules for common vfx software, and general CMake utility code. [LGPL][LGPL]
* [jedbrown/cmake-modules](https://github.com/jedbrown/cmake-modules) - CMake modules for some scientific libraries. [BSD2][BSD-2-Clause]
* [chadmv/cgcmake](https://github.com/chadmv/cgcmake) - CMake modules for common applications related to computer graphics. [MIT][MIT]
* [sakra/FindMathematica](https://github.com/sakra/FindMathematica) - CMake module for Mathematica. [MIT][MIT]
* [KDE/extra-cmake-modules](https://github.com/KDE/extra-cmake-modules) - Extra modules and scripts for CMake. [BSD3][BSD-3-Clause]
* [julp/FindICU.cmake](https://github.com/julp/FindICU.cmake) - A CMake module to find International Components for Unicode (ICU) Library. [BSD2][BSD-2-Clause]
* [justusc/FindTBB](https://github.com/justusc/FindTBB) - CMake find module for Intel Threading Building Blocks. [MIT][MIT]
* [hanjianwei/cmake-modules](https://github.com/hanjianwei/cmake-modules) - CMake module collection. [MIT][MIT]

## Utility Scripts

These provide a wide range of functionality - from dealing with compiler flags to using tools. Some also contain modules.

* [sakra/cotire](https://github.com/sakra/cotire) - Cotire (compile time reducer) is a CMake module that speeds up the build process of CMake based build systems by fully automating techniques as precompiled headers and unity builds for C and C++. [MIT][MIT]
* [onqtam/ucm](https://github.com/onqtam/ucm) - For managing compiler/linker flags, collecting sources, precompiled headers, unity builds and others. [MIT][MIT]
* [toeb/cmakepp](https://github.com/toeb/cmakepp) - An Enhancement Suite for the CMake Build System. [MIT][MIT]
* [ruslo/sugar](https://github.com/ruslo/sugar) - CMake tools and examples: collecting source files, warnings suppression, etc. [BSD2][BSD-2-Clause]
* [Crascit/DownloadProject](https://github.com/Crascit/DownloadProject) - CMake module for downloading an external project's source at configure time. [MIT][MIT]
* [janelia-flyem/buildem](https://github.com/janelia-flyem/buildem) - A modular CMake-based system that leverages ExternalProject to simplify builds. [LICENSE](https://github.com/janelia-flyem/buildem/blob/master/LICENSE.txt)
* [JoakimSoderberg/coveralls-cmake](https://github.com/JoakimSoderberg/coveralls-cmake) - Coveralls JSON coverage generator and uploader for CMake. [MIT][MIT]
* [foonathan/compatibility](https://github.com/foonathan/compatibility) - An improved version of cmake-compile-features. [LICENSE](https://github.com/foonathan/compatibility/blob/master/LICENSE)
* [Tronic/cmake-modules](https://github.com/Tronic/cmake-modules) - LibFindMacros development repository and other cool CMake stuff. [LICENSE](https://github.com/Tronic/cmake-modules/blob/master/LibFindMacros.cmake#L2)
* [UCL/GreatCMakeCookOff](https://github.com/UCL/GreatCMakeCookOff) - This is a repository of useful and less than useful CMake recipes. [MIT][MIT]
* [polysquare/cppcheck-target-cmake](https://github.com/polysquare/cppcheck-target-cmake) - Per-target CPPCheck for CMake. [MIT][MIT]
* [polysquare/clang-tidy-target-cmake](https://github.com/polysquare/clang-tidy-target-cmake) - Add clang-tidy checks to a target using CMake. [MIT][MIT]
* [polysquare/cmake-unit](https://github.com/polysquare/cmake-unit) - A unit testing framework for CMake. [MIT][MIT]
* [polysquare/cmake-header-language](https://github.com/polysquare/cmake-header-language) - CMake macro to determine the language of a header file. [MIT][MIT]
* [polysquare/tooling-cmake-util](https://github.com/polysquare/tooling-cmake-util) - Utility and common library for all polysquare CMake tools. [MIT][MIT]
* [polysquare/iwyu-target-cmake](https://github.com/polysquare/iwyu-target-cmake) - CMake integration for include-what-you-use. [MIT][MIT]
* [arsenm/sanitizers-cmake](https://github.com/arsenm/sanitizers-cmake) - CMake module to enable sanitizers for binary targets. [MIT][MIT]
* [larsch/cmake-precompiled-header](https://github.com/larsch/cmake-precompiled-header) - Visual Studio and GCC precompiled header macro. [LICENSE](https://github.com/larsch/cmake-precompiled-header/blob/master/PrecompiledHeader.cmake#L31)
* [nanoant/CMakePCHCompiler](https://github.com/nanoant/CMakePCHCompiler) - CMake precompiled headers via custom compiler extension - with reuse support! [MIT][MIT]
* [RWTH-ELP/CMake-codecov](https://github.com/RWTH-ELP/CMake-codecov) - Enables code coverage and generates coverage reports with CMake targets. [GPL][GPL]
* [puppetlabs/leatherman](https://github.com/puppetlabs/leatherman) - A collection of C++ and CMake utility libraries. [APACHE 2][APACHE 2]

## Toolchains

* [taka-no-me/android-cmake](https://github.com/taka-no-me/android-cmake) - CMake toolchain file and other scripts for the Android NDK. [BSD3][BSD-3-Clause]
* [cristeab/ios-cmake](https://github.com/cristeab/ios-cmake) - A toolchain file and examples using CMake for iOS development. [BSD3][BSD-3-Clause]
* [LaurentGomila/qt-android-cmake](https://github.com/LaurentGomila/qt-android-cmake) - For building and deploying Qt based apps on Android without QtCreator. [LICENSE](https://github.com/LaurentGomila/qt-android-cmake/blob/master/license.txt)
* [lachs0r/mingw-w64-cmake](https://github.com/lachs0r/mingw-w64-cmake) - CMake-based MinGW-w64 Cross Toolchain - to build Windows binaries of mpv. [ISC][ISC]
* [mkleemann/cmake-avr](https://github.com/mkleemann/cmake-avr) - CMake toolchain for AVR. [LICENSE](https://github.com/mkleemann/cmake-avr/blob/master/LICENSE)
* [francoiscampbell/arduino-cmake](https://github.com/francoiscampbell/arduino-cmake) - This is the CMake project settings for the Arduino platform. [MPL][MPL]
* [ruslo/polly](https://github.com/ruslo/polly) - Collection of CMake toolchain files and scripts for cross-platform build and CI testing. [BSD2][BSD-2-Clause]
* [mosra/toolchains](https://github.com/mosra/toolchains) - For crosscompiling with CMake. They are meant to be mainly used on ArchLinux. [NO LICENSE]
* [staticlibs/cmake](https://github.com/staticlibs/cmake/tree/master/toolchains) - Collection of CMake toolchain files, mostly for static linking. [APACHE 2][APACHE 2]

## Tutorials/Examples/Templates

* [cginternals/cmake-init](https://github.com/cginternals/cmake-init) - Template for reliable, cross-platform C++ project setup using CMake. [LICENSE](https://github.com/cginternals/cmake-init/blob/master/LICENSE)
* [Akagi201/learning-cmake](https://github.com/Akagi201/learning-cmake) - This is a simple CMake practice project which contains some different scenarios. [GPL2][GPL2]
* [skebanga/cmake_test](https://github.com/skebanga/cmake_test) - A small example project using CMake. [NO LICENSE]
* [forexample/android-cmake](https://github.com/forexample/android-cmake) - Examples of using [ruslo/hunter](https://github.com/ruslo/hunter) package manager for an Android application. [BSD2][BSD-2-Clause]
* [forexample/hunter-simple](https://github.com/forexample/hunter-simple) - Example of downloading/installing dependencies using [ruslo/hunter](https://github.com/ruslo/hunter) package manager. [BSD2][BSD-2-Clause]
* [ruslo/weather](https://github.com/ruslo/weather) - Example of using [Hunter](http://github.com/ruslo/hunter) cross-platform package manager for CMake to build application which use Boost, CppNetlib.URI, GTest, JSON Spirit. Platforms: Windows (Visual Studio), Linux, Mac OS X + iOS. [BSD2][BSD-2-Clause]
* [forexample/package-example](https://github.com/forexample/package-example) - Config mode of find_package command (examples for [this](http://stackoverflow.com/questions/20746936/cmake-of-what-use-is-find-package-if-you-need-to-specify-cmake-module-path-an) SO question). [NO LICENSE]
* [OutOfOrder/CMakeTemplates](https://github.com/OutOfOrder/CMakeTemplates) - A set of initial CMake templates that I use for every game port I work on. [NO LICENSE]
* [krux02/minimal_cmake_example](https://github.com/krux02/minimal_cmake_example) - A minimal CMake example, that covers dependencies and packaging. [CC0-1.0][CC0-1.0]
* [bast/cmake-example](https://github.com/bast/cmake-example) - Example project which demonstrates various CMake features. [BSD3][BSD-3-Clause]
* [ttroy50/cmake-examples](https://github.com/ttroy50/cmake-examples) - Useful CMake examples in a tutorial format. [MIT][MIT]
* [district10/cmake-templates](https://github.com/district10/cmake-templates) - Some CMake Templates. Qt, Boost, OpenCV, C++11, etc. [MIT][MIT]
* [Barthelemy/CppProjectTemplate](https://github.com/Barthelemy/CppProjectTemplate) - Basic, but working, C++ project using CMake, boost and Doxygen. [MIT][MIT]
* [euler0/mini-cmake-qt](https://github.com/euler0/mini-cmake-qt) - A minimal CMake template for Qt 5 projects. [LICENSE](https://github.com/euler0/mini-cmake-qt/blob/master/LICENSE)
* [cognitivewaves/CMake-VisualStudio-Example](https://github.com/cognitivewaves/CMake-VisualStudio-Example) - CMake example for Visual Studio developers - [blog post](http://cognitivewaves.wordpress.com/cmake-and-visual-studio/). [NO LICENSE]
* [NewProggie/Cpp-Project-Template](https://github.com/NewProggie/Cpp-Project-Template) - C++ bootstrap project template including CMake build system. [MIT][MIT]
* [cmake-basis/BASIS](https://github.com/cmake-basis/BASIS) - CMake [BASIS](https://cmake-basis.github.io) makes it easy to create sharable software and libraries that work together. [BSD2][BSD-2-Clause]
* [ArthurSonzogni/OpenGL_CMake_Skeleton](https://github.com/ArthurSonzogni/OpenGL_CMake_Skeleton) -  A ready to use CMake skeleton using GLFW, Glew and glm. [MIT][MIT]
* [JoakimSoderberg/coveralls-cmake-example](https://github.com/JoakimSoderberg/coveralls-cmake-example) - Example project for [coveralls-cmake](https://github.com/JoakimSoderberg/coveralls-cmake). [NO LICENSE]
* [kartikkumar/cppbase](https://github.com/kartikkumar/cppbase) - A template for a simple CMake-based C++ project. [MIT][MIT]
* [maxbader/Arduino-CMake-Template](https://github.com/maxbader/Arduino-CMake-Template) - Starting point for Arduino development using CMake. [NO LICENSE]
* [fletcher/c-template](https://github.com/fletcher/c-template) - Boilerplate to set up a c project, include CuTest, cmake build setup. [MIT][MIT]
* [duckie/cpp_project_template](https://github.com/duckie/cpp_project_template) - A simple template to start quickly a C++ project managed by CMake. [NO LICENSE]

## Other

* [coderefinery/autocmake](https://github.com/coderefinery/autocmake) - Using a autocmake.yml file [Autocmake](http://autocmake.readthedocs.io/en/latest/) composes CMake building blocks into a CMake project and generates CMakeLists.txt as well as a setup script, which serves as a front-end to CMakeLists.txt. [BSD3][BSD-3-Clause]
* [kmorel/UseLATEX](https://github.com/kmorel/UseLATEX) - A collection of CMake macros to simplify building LaTeX files. [BSD3][BSD-3-Clause]
* [python-cmake-buildsystem/python-cmake-buildsystem](https://github.com/python-cmake-buildsystem/python-cmake-buildsystem) - A replacement buildsystem for CPython. [APACHE 2][APACHE 2]
* [jesperes/protobuf-cmake](https://github.com/jesperes/protobuf-cmake) - CMake build support for Google Protobufs. [BSD3][BSD-3-Clause]
* [cjntaylor/node-cmake](https://github.com/cjntaylor/node-cmake) - CMake-based build system for node.js native modules. [ISC][ISC]
* [Lindydancer/cmake-font-lock](https://github.com/Lindydancer/cmake-font-lock) - Advanced syntax coloring support for CMake scripts inside Emacs. [GPL][GPL]
* [ObKo/stm32-cmake](https://github.com/ObKo/stm32-cmake) - Used to develop applications for the STM32 - ST's ARM Cortex-M0(3,4,7) MCUs. [NO LICENSE]
* [rastersoft/autovala](https://github.com/rastersoft/autovala) - A program that automatically generates CMake configuration files for your Vala project. [GPL][GPL]
* [ros/catkin](https://github.com/ros/catkin) - A CMake-based build system that is used to build all packages in Robot Operating System (ROS). [BSD3][BSD-3-Clause]
* [jlblancoc/suitesparse-metis-for-windows](https://github.com/jlblancoc/suitesparse-metis-for-windows) - CMake scripts for painless usage of SuiteSparse+METIS. [BSD3][BSD-3-Clause]
* [thewtex/cython-cmake-example](https://github.com/thewtex/cython-cmake-example) - Utilities and example for using CMake to build Cython modules. [LICENSE](https://github.com/thewtex/cython-cmake-example/blob/master/LICENSE)
* [bjornblissing/osg-3rdparty-cmake](https://github.com/bjornblissing/osg-3rdparty-cmake) - CMake scripts for building OpenSceneGraph third party libraries. [NO LICENSE]
* [dcarp/cmake-d](https://github.com/dcarp/cmake-d) - CMake for D2. [MIT][MIT]
* [h4tr3d/cmakeprojectmanager2](https://github.com/h4tr3d/cmakeprojectmanager2) - Enhanced CMake Project Manager plugin for Qt Creator. [NO LICENSE]
* [robotology/ycm](https://github.com/robotology/ycm) - Extra CMake Modules for [Yet Another Robot Platform](https://github.com/robotology/yarp) and friends. [BSD2][BSD-2-Clause]
* [richq/cmake-lint](https://github.com/richq/cmake-lint) - Check for coding style issues in CMake files. cmakelint requires Python. [APACHE 2][APACHE 2]
* [kbenzie/git-cmake-format](https://github.com/kbenzie/git-cmake-format) - Integrate clang-format into your CMake project hosted in a git repository. [LICENSE](https://github.com/kbenzie/git-cmake-format/blob/master/license.txt)
* [nemequ/configure-cmake](https://github.com/nemequ/configure-cmake) - configure-cmake is an autotools-style configure script for CMake-based projects. [CC0-1.0][CC0-1.0]
* [wjakob/tbb](https://github.com/wjakob/tbb) - Threading Building Blocks with CMake build. [NO LICENSE]
* [snikulov/sqlite.cmake.build](https://github.com/snikulov/sqlite.cmake.build) - CMake script for sqlite amalgamation. [NO LICENSE]
* [polysquare/cmake-ast](https://github.com/polysquare/cmake-ast) - Python module to reduce a CMake file to an AST. [MIT][MIT]

[ISC]: https://opensource.org/licenses/ISC
[GPL]: https://www.gnu.org/licenses/gpl-3.0.html
[GPL2]: https://www.gnu.org/licenses/old-licenses/gpl-2.0.html
[LGPL]: https://www.gnu.org/licenses/lgpl-3.0.en.html
[MIT]: https://opensource.org/licenses/MIT
[BOOST]: http://www.boost.org/LICENSE_1_0.txt
[BSD-2-Clause]: https://opensource.org/licenses/BSD-2-Clause
[BSD-3-Clause]: https://opensource.org/licenses/BSD-3-Clause
[APACHE 2]: http://www.apache.org/licenses/LICENSE-2.0
[CC0-1.0]: https://creativecommons.org/publicdomain/zero/1.0/
[MPL]: https://www.mozilla.org/en-US/MPL/2.0/
