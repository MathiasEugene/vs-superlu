# SuperLU for Visual Studio

This is a Visual Studio solution for [SuperLU](https://github.com/xiaoyeli/superlu).

## Instructions

The repository does not contain the SuperLU source code. It can be obtained from https://github.com/xiaoyeli/superlu. The Visual Studio solution was tested with SuperLU version 5.2.2, but should also work with newer versions. Download the [latest](https://github.com/xiaoyeli/superlu/archive/master.zip) version and extract it to the `src` folder (a subfolder should be created automatically, rename it to `SuperLU`). To check if everything is in its right place, make sure that the file `src/SuperLU/README` exists.

Pre-compiled binaries for windows users can be found [here](http://wo80.bplaced.net/math/packages.html).

## Why?

The project was created to maintain SuperLU builds matching the [CSparse.Interop](https://github.com/wo80/csparse-interop) bindings for C#.
