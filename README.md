# Psy-Q PSYLINK Command File Maker

[![Build Status](https://github.com/devon-artmeier/mkpsylink/actions/workflows/cmake-multi-platform.yml/badge.svg)](https://github.com/devon-artmeier/mkpsylink/actions/workflows/cmake-multi-platform.yml)

This is a tool to create a Psy-Q PSYLINK command file from a list of object files and instructions file.

## Usage

    mkpsylink -c [instructions] -o [output]  [object files]
    
        -c [instructions] - Linker instructions file
        -o [output]       - Output file
        [object files]    - List of object files to link

## Build Instructions

CMake is required to build this.

* On Windows, you can run "make.bat" and the built executable will be put in the "out/bin" folder.
* On other systems, you can call "make" and then "make install".
