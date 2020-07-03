# DDEUtilsJF

## Introduction

This is a reimplementation of the DDEUtils for RISC OS. It was written so that
it could be used by applications when the user didn't own the Acorn Desktop
Development Environment. The throwback interface, and extended command line
were very useful.

To a lesser extent the 'prefix' support was useful, and the implementation
provided in this module is different in its behaviour to that of the original.

## Usage

* Load the module into a 26bit machine.

## Continuous Integration (CI) support

This release is intended to demonstrate the continuous integration environment
provided by the build.riscos.online system. Two mechanisms are provided for
building the module - through GitLab CI, and through GitHub's workflows.

Documentation for the `.robuild.yaml` file format can be found on the
[build.riscos.online website](https://build.riscos.online/robuildyaml.html),
and the example here just invokes the AMU tool to perform the build.

* For GitHub workflows, see the file `.github/workflows/ci.yml`.
* For GitLab CI, see the file `.gitlab-ci.yml`.
