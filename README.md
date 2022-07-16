# Latte compiler

A toy, Java-like, "Latte" language compiler implemented in Haskell.
This project was created as a solution to the [large assignment](https://www.mimuw.edu.pl/~ben/Zajecia/Mrj2021/latte.html) for the "Compiler construction" course at the University of Warsaw. 

## Build
To build the `latc` binary from source simply run `make`.

## Library
`lib` directory contains a runtime library with all builtin functions.

## Dependencies
All required dependencies are described in `package.yaml` which was used to generate cabal config file using `hpack`.
Most notably the compiler makes use of `mtl` and `lens` packages.
