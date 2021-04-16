# AFCL Editor

This repository contains the implementation of the IDE for the AFCL DSL made with [JetBrains MPS](https://www.jetbrains.com/mps/). It allows an easy implementation of workflows, which can be exported to the original [yaml based representation](https://apollowf.github.io/learn.html) for the [Apollo Platform](https://github.com/Apollo-Workflows).


## Build process

Information about the build process can be found [here](docs/build.md)

## Tutorial

A tutorial for the editor can be found [here](docs/tutorial.md).

Additionally you can also have a look at the some example workflows within this repository.

## Project Structure

An overview about the project structure is presented [here](docs/project_structure.md).

## Features

- [x] Workflow block
- [x] Data output references/auto completion
- [x] Base Functions
- Supported Types
    - [x] String
    - [x] Boolean
    - [x] Number 
    - [x] Array
- Compound functions:
    - [x] If-then-else block
    - [ ] Switch block
    - [ ] For block
    - [ ] While block
    - [x] ParallelFor block
- [ ] Properties and Constraints
- [x] Building IDE
- [x] Export to YAML

