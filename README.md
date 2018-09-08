# SuperLU for Visual Studio

This is a Visual Studio solution for [SuperLU](http://crd-legacy.lbl.gov/~xiaoye/SuperLU/).

## Instructions

The repository does not contain the SuperLU source code. It can be obtained from http://crd-legacy.lbl.gov/~xiaoye/SuperLU/#superlu. The Visual Studio solution was created for SuperLU version [5.2.1](http://crd-legacy.lbl.gov/~xiaoye/SuperLU/superlu_5.2.1.tar.gz), but should also work with newer versions. Download the latest version and extract it to the `src` folder (a subfolder `SuperLU_5.2.1` should be created automatically, rename it to `SuperLU`). To check if everything is in its right place, make sure that the file `src/SuperLU/README` exists.

## Why?

The project was created to maintain SuperLU builds matching the [CSparse.Interop](https://github.com/wo80/csparse-interop) bindings for C#.
