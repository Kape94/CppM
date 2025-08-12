# CppM

A CLI helper tool for easy management of C++ project, inspired on npm workflow.

The intent of this project is to provide an easy workflow for dealing with dependency and build management for C++ projects, so the main focus is easy usage, rather than full flexibility. 
The helper tool basically uses vcpkg and cmake under the hood, so you'll be able to structure and scale your project using these tools.

## Requirements

In order to use this tool, you'll need to have git installed and accessible through command line, this is the only requirement.
You don't need to have cmake installed, since the CppM tool leverages a Vcpkg's local cmake installation to build the project as well.

## Installation

In order to install CppM on your system, you can use pip:

```bash
pip install cppm
```
