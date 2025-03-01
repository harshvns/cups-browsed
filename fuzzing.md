# Fuzzing cups-browsed

This document explains how to build and run the fuzzing harness for `cups-browsed` using libFuzzer.

## Prerequisites
- **Compiler**: Clang (`clang` and `clang++`).

# Building the fuzzer

make -f Makefile.fuzz

# Running the fuzzer

./fuzz_cups_browsed corpus_dir/

# Cleaning up

make -f Makefile.fuzz clean