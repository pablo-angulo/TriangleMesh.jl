# TriangleMesh.jl

*TriangleMesh* is written to provide a convenient mesh generation and refinement tool for Delaunay and constraint Delaunay meshes in Julia. Please see the documentation.

| **Documentation** | **Build Status** | **Code Coverage**| **Windows Build** | 
|:-----------------:|:----------------:|:----------------:|:-----------------:|
| [![][docs-stable-img]][docs-stable-url] [![][docs-latest-img]][docs-latest-url] | [![][travis-img]][travis-url] |  [![][codecov-img]][codecov-url] | [![AppVeyor Build status][appveyor-img]][appveyor] |

### Installation

*TriangleMesh* is not officialy registered yet. To install run
```julia
Pkg.clone("https://github.com/konsim83/TriangleMesh.jl.git")
```
and then run
```julia
Pkg.build("TriangleMesh")
```
After the build passed successfully type
```julia
using TriangleMesh
```
to use the package. If you are having trouble please open an [issue](https://github.com/konsim83/TriangleMesh.jl/issues).

### TriangleMesh on Windows

To build TriangleMesh you need [VC++ for Python](https://www.microsoft.com/en-us/download/details.aspx?id=44266). It is for free and easy to install.

[docs-latest-img]: https://img.shields.io/badge/docs-latest-blue.svg
[docs-latest-url]: https://konsim83.github.io/TriangleMesh.jl/latest

[docs-stable-img]: https://img.shields.io/badge/docs-stable-blue.svg
[docs-stable-url]: https://konsim83.github.io/TriangleMesh.jl/stable

[travis-img]: https://travis-ci.org/konsim83/TriangleMesh.jl.svg?branch=master
[travis-url]: https://travis-ci.org/konsim83/TriangleMesh.jl

[codecov-img]: https://codecov.io/gh/konsim83/TriangleMesh.jl/branch/master/graph/badge.svg
[codecov-url]: https://codecov.io/gh/konsim83/TriangleMesh.jl

[appveyor]: https://ci.appveyor.com/project/konsim83/TriangleMesh.jl
[appveyor-img]: https://ci.appveyor.com/api/projects/status/qumgv56ma7dg07qg/branch/master?svg=true
