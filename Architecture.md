# Global Architecture

## Parsing
From files versions, commits,... , it should produce atomic evolutions.

- Semantic
- Refminer
- Spoon https://github.com/INRIA/spoon

## Composition of Evolutions
From atomic evolutions and other data, it should compose evolutions.

- Refminer
- Coming https://github.com/SpoonLabs/coming

## Impact Analysis
Given evolutions, it should associate impacted tests.

- Dynamic analysis (see m1_internship)
- Static analysis done by compilers on their source language

## Co-evolution of Tests
Given evolutions and their relation with tests, it should repair tests.

- Manual
- Approaches ref in the state of the art (patterns, learning,...)
