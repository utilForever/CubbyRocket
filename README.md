# CubbyRocket

<img src="./Medias/Logos/Logo.png" width=256 height=256 />

[![License](https://img.shields.io/badge/Licence-MIT-blue.svg)](https://github.com/utilForever/CubbyRocket/blob/main/LICENSE) ![Windows](https://github.com/utilForever/CubbyRocket/workflows/Windows/badge.svg) ![Ubuntu](https://github.com/utilForever/CubbyRocket/workflows/Ubuntu/badge.svg) ![macOS](https://github.com/utilForever/CubbyRocket/workflows/macOS/badge.svg) ![Ubuntu - Codecov](https://github.com/utilForever/CubbyRocket/workflows/Ubuntu%20-%20Codecov/badge.svg) [![Build Status](https://travis-ci.com/utilForever/CubbyRocket.svg?branch=main)](https://travis-ci.com/utilForever/CubbyRocket)

[![codecov](https://codecov.io/gh/utilForever/CubbyRocket/branch/main/graph/badge.svg)](https://codecov.io/gh/utilForever/CubbyRocket)
[![Codacy Badge](https://app.codacy.com/project/badge/Grade/ebcad6f87a4a41eab8811162c57c0ba8)](https://www.codacy.com/gh/utilForever/CubbyRocket/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=utilForever/CubbyRocket&amp;utm_campaign=Badge_Grade)
[![Total alerts](https://img.shields.io/lgtm/alerts/g/utilForever/CubbyRocket.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/utilForever/CubbyRocket/alerts/)
[![Language grade: C/C++](https://img.shields.io/lgtm/grade/cpp/g/utilForever/CubbyRocket.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/utilForever/CubbyRocket/context:cpp)
[![CodeFactor](https://www.codefactor.io/repository/github/utilforever/CubbyRocket/badge)](https://www.codefactor.io/repository/github/utilforever/CubbyRocket)

[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=CubbyRocket&metric=alert_status)](https://sonarcloud.io/dashboard?id=CubbyRocket) [![Lines of Code](https://sonarcloud.io/api/project_badges/measure?project=CubbyRocket&metric=ncloc)](https://sonarcloud.io/dashboard?id=CubbyRocket) [![Maintainability Rating](https://sonarcloud.io/api/project_badges/measure?project=CubbyRocket&metric=sqale_rating)](https://sonarcloud.io/dashboard?id=CubbyRocket) [![Reliability Rating](https://sonarcloud.io/api/project_badges/measure?project=CubbyRocket&metric=reliability_rating)](https://sonarcloud.io/dashboard?id=CubbyRocket) [![Security Rating](https://sonarcloud.io/api/project_badges/measure?project=CubbyRocket&metric=security_rating)](https://sonarcloud.io/dashboard?id=CubbyRocket)

CubbyRocket is a simple rocket simulation engine from water rocket to satellite. The code is built on C++17 and can be compiled with commonly available compilers such as g++, clang++, or Microsoft Visual Studio. CubbyRocket currently supports macOS (10.14 or later), Ubuntu (18.04 or later), Windows (Visual Studio 2017 or later), and Windows Subsystem for Linux (WSL). Other untested platforms that support C++17 also should be able to build CubbyRocket.

## Key Features

  * C++17 based simple rocket simulation engine
  * C++ and Python API

## Quick Start

You will need CMake to build the code. If you're using Windows, you need Visual Studio 2017 in addition to CMake.

First, clone the code:

```
git clone https://github.com/utilForever/CubbyRocket.git --recursive
cd CubbyRocket
```

### C++ API

For macOS or Linux or Windows Subsystem for Linux (WSL):

```
mkdir build
cd build
cmake ..
make
```

For Windows:

```
mkdir build
cd build
cmake .. -G"Visual Studio 15 2017 Win64"
MSBuild CubbyRocket.sln /p:Configuration=Release
```

### Docker

```
docker pull utilforever/CubbyRocket:latest
```

## Documentation

TBA

## How To Contribute

Contributions are always welcome, either reporting issues/bugs or forking the repository and then issuing pull requests when you have completed some additional coding that you feel will be beneficial to the main project. If you are interested in contributing in a more dedicated capacity, then please contact me.

## Contact

You can contact me via e-mail (utilForever at gmail.com). I am always happy to answer questions or help with any issues you might have, and please be sure to share any additional work or your creations with me, I love seeing what other people are making.

## License

<img align="right" src="http://opensource.org/trademarks/opensource/OSI-Approved-License-100x137.png">

The class is licensed under the [MIT License](http://opensource.org/licenses/MIT):

Copyright &copy; 2021 CubbyRocket Team

  * [Chris Ohk](http://github.com/utilForever)
  * [Changhyun Lim](https://github.com/aiden0206)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
