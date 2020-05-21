# Non-Modern (but still awesome) CMake [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[<img src="https://rawgit.com/onqtam/awesome-cmake/master/cmake-logo.svg" align="right" width="100">](https://cmake.org/)

> This is an archive of pre-modern [CMake](https://cmake.org/) scripts, modules, examples and others

Your contributions are highly welcome (first see [CONTRIBUTING.md](CONTRIBUTING.md)).

This file contains links worth taking a look, but they use obsolete practices which are considered non-modern - like not using `target_*`-based dependency management - see [`#16`](https://github.com/onqtam/awesome-cmake/issues/16) and [`#42`](https://github.com/onqtam/awesome-cmake/pull/42) for more details.

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


## Resources

* [Article](https://juan-medina.com/2017/07/01/moderncppci/) - Modern C++ CI (although it uses non-modern CMake like ```include_directories()```).
* [Article](https://www.jetbrains.com/help/clion/quick-cmake-tutorial.html) - Quick CMake Tutorial - from JetBrains - the company behind CLion.

## Package Management / Build Systems


## Modules

* [vfxcmake](https://github.com/nerdvegas/vfxcmake) - CMake Find modules for common vfx software, and general CMake utility code. [```[LGPL]```][LGPL]
* [sdl2-cmake-scripts](https://github.com/tcbrindle/sdl2-cmake-scripts) - CMake scripts for finding the SDL2, SDL2_image and SDL2_ttf libraries and headers. [```[BSD2]```][BSD-2-Clause]

## Utility Scripts

* [leatherman](https://github.com/puppetlabs/leatherman) - Collection of C++ and CMake utility libraries. [```[APACHE2]```][APACHE2]


## Toolchains

## Examples / Templates

* [ModernCppCI](https://github.com/LearningByExample/ModernCppCI) - An example of doing a Modern C++ project with CI (although it uses non-modern CMake like ```include_directories()```). [```[MIT]```][MIT]
* [cleanCppProject](https://github.com/kracejic/cleanCppProject) - A project template using modern CMake, with packaging, tests, docs, static/dynamic analysis, CI. [```[MIT]```][MIT]
* [ci_helloworld](https://github.com/ainfosec/ci_helloworld) - A simple example of how to setup a complete CI environment for C and C++. [```[MIT]```][MIT]
* [cpp_project_template](https://github.com/duckie/cpp_project_template) - Simple template to start quickly a C++ project managed by CMake. [```[MIT]```][MIT]
* [c-template](https://github.com/fletcher/c-template) - Boilerplate to set up a c project, include CuTest, CMake build setup. [```[MIT]```][MIT]
* [Arduino-CMake-Template](https://github.com/maxbader/Arduino-CMake-Template) - Starting point for Arduino development using CMake. ```[NO LICENSE]```
* [cppbase](https://github.com/kartikkumar/cppbase) - Template for a simple CMake-based C++ project. [```[MIT]```][MIT]
* [coveralls-cmake-example](https://github.com/JoakimSoderberg/coveralls-cmake-example) - Example project for [coveralls-cmake](https://github.com/JoakimSoderberg/coveralls-cmake). ```[NO LICENSE]```
* [OpenGL_CMake_Skeleton](https://github.com/ArthurSonzogni/OpenGL_CMake_Skeleton) -  A ready to use CMake skeleton using GLFW, Glew and glm. [```[MIT]```][MIT]
* [Cpp-Project-Template](https://github.com/NewProggie/Cpp-Project-Template) - C++ bootstrap project template including CMake build system. [```[MIT]```][MIT]
* [CMake-VisualStudio-Example](https://github.com/cognitivewaves/CMake-VisualStudio-Example) - CMake example for Visual Studio developers - [blog post](http://cognitivewaves.wordpress.com/cmake-and-visual-studio/). ```[NO LICENSE]```
* [CppProjectTemplate](https://github.com/Barthelemy/CppProjectTemplate) - Basic, but working, C++ project using CMake, boost and Doxygen. [```[MIT]```][MIT]
* [cmake-templates](https://github.com/district10/cmake-templates) - Some CMake Templates. Qt, Boost, OpenCV, C++11, etc. [```[MIT]```][MIT]
* [CMakeTemplates](https://github.com/OutOfOrder/CMakeTemplates) - Set of initial CMake templates that I use for every game port I work on. ```[NO LICENSE]```
* [weather](https://github.com/abandonware-pjz37/weather) - Example of using [Hunter](http://github.com/ruslo/hunter) cross-platform package manager for CMake to build application which use Boost, CppNetlib.URI, GTest, JSON Spirit. Platforms: Windows (Visual Studio), Linux, Mac OS X + iOS. [```[BSD2]```][BSD-2-Clause]
* [cmake_test](https://github.com/skebanga/cmake_test) - Small example project using CMake. ```[NO LICENSE]```
* [learning-cmake](https://github.com/Akagi201/learning-cmake) - This is a simple CMake practice project which contains some different scenarios. [```[GPL2]```][GPL2]


## Other

* [python-cmake-buildsystem](https://github.com/python-cmake-buildsystem/python-cmake-buildsystem) - Replacement buildsystem for CPython. [```[APACHE2]```][APACHE2]
* [protobuf-cmake](https://github.com/jesperes/protobuf-cmake) - CMake build support for Google Protobufs. [```[BSD3]```][BSD-3-Clause]
* [stm32-cmake](https://github.com/ObKo/stm32-cmake) - Used to develop applications for the STM32 - ST's ARM Cortex-M0(3,4,7) MCUs. [```[MIT]```][MIT]
* [cython-cmake-example](https://github.com/thewtex/cython-cmake-example) - Utilities and example for using CMake to build Cython modules. [```[LICENSE]```](https://github.com/thewtex/cython-cmake-example/blob/master/LICENSE)
* [tbb](https://github.com/wjakob/tbb) - Threading Building Blocks with CMake build. [```[APACHE2]```][APACHE2]
* [sqlite.cmake.build](https://github.com/snikulov/sqlite.cmake.build) - CMake script for sqlite amalgamation. ```[NO LICENSE]```
* [cmake_format](https://github.com/cheshirekow/cmake_format) - Source code formatter for CMakeLists.txt files. [```[GPL]```][GPL]
* [cmrc](https://github.com/vector-of-bool/cmrc) - A Resource Compiler in a Single CMake Script (compile arbitrary data into a program). [```[MIT]```][MIT]

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
