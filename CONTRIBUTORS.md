# Contributors
This file describes the contributors to the HELICS library and the software used as part of this project
If you would like to contribute to the HELICS project see [CONTRIBUTING](CONTRIBUTING.md)
## Individual contributors
### Pacific Northwest National Lab
-   Jeff Daily (Now AMD)

### Lawrence Livermore National Lab
-   Ryan Mast
-   Philip Top

### National Renewable Energy Lab
-   Dheepak Krishnamurthy

## Cmake-helpers based on code from the following repositories

Several cmake scripts came from other sources and were either used or modified for use in HELICS.
-   Lars Bilke [CodeCoverage.cmake](https://github.com/bilke/cmake-modules/blob/master/CodeCoverage.cmake)
-   Viktor Kirilov, useful cmake macros [ucm](https://github.com/onqtam/ucm)  particularly for the set_runtime macro to use static runtime libraries
-   scripts for cloning git repositories are included from [tschuchortdev/cmake_git_clone](https://github.com/tschuchortdev/cmake_git_clone) used with [MIT](https://github.com/tschuchortdev/cmake_git_clone/blob/master/LICENSE.TXT) License
-   Some scripts for including google test were borrowed from [CLI11](https://github.com/CLIUtils/CLI11) and the addGoogleBenchmark was based on the same source
