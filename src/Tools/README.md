The `src/Tools` folder contains a simple C# program to manage some aspects of the solution. It can be compiled by running the `build` script from the command line.

The executable `mgmt.exe` can be used with the following commands:

```
mgmt clean
mgmt clean -default =  Remove unused files from SuperLU
mgmt clean -build   =  Remove build artifacts (obj files etc.)
mgmt clean -docs    =  Remove docs from SuperLU
mgmt clean -all     =  Combines all above options

mgmt update
mgmt update -check    =  Check installed version of SuperLU
mgmt update -download =  Download latest version of SuperLU
```
