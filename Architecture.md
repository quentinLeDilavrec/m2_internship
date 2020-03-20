# Global Architecture

## Parsing
From files versions, commits,... , it should produce atomic evolutions.

- Semantic
- Refminer
- Spoon https://github.com/INRIA/spoon
  - Granularity: invocation,parameter
- ChangeDistiller
  - Granularity: statement
  - ref: 2 from martinez2019coming
- Eclipse JDT
  - ref: 1 of martinez2019coming
  - Granularity: finer than ChangeDistiller
- repo mining cite:pietri2019software,martinez2019coming
- PyDriller https://github.com/ishepard/pydriller
  - ref: 17 of martinez2019coming
- Git-of-theseus https://github.com/erikbern/git-of-theseus/
- CVSAnalY https://github.com/MetricsGrimoire/CVSAnalY
- Hercules https://github.com/src-d/hercules

## Composition of Evolutions
From atomic evolutions and other data, it should compose evolutions.

- Refminer
- Coming https://github.com/SpoonLabs/coming cite:martinez2019coming
  - on top of: Spoon through GTSpoon, GumTree
  - pattern: written in XML
  - good: evaluation of changes
  - good: show example of changes on if blocks
  - bad: some more diversity in examples
- ChangeDistiller

## Impact Analysis
Given evolutions, it should associate impacted tests.

- Dynamic analysis (see m1_internship)
- Static analysis done by compilers on their source language

## Co-evolution of Tests
Given evolutions and their relation with tests, it should repair tests.

- Manual
- Approaches ref in the state of the art (patterns, learning,...)
