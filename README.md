# Platform
This is the meta project that handles the different platform codebases.
It also contains the config for VSC, in order to setup tools and environments

## Setup
Run `meta git clone https://gitlab.com/r2m/platform/main.git` in your terminal.
It will create a folder called `platform` in your CWD and clone the codebases in to that.

## Commands
For a full set of commands, please see the [meta documentation](https://github.com/mateodelnorte/meta).

- `yarn gh` - Alias for [meta-gh](https://github.com/mateodelnorte/meta-gh) that provides utilities to work with github issues etc.
- `yarn add:all` - Install a package in all subprojects (equivalent to running `yarn add` in all the projects). 
- `meta git status` - Runs `git status` on all sub projects.
- `meta git branch` - View what branches exist on all sub projects.
- `meta git checkout -b [branch-name]` - create a new branch in each sub project. Usefull when working on features that covers several projects.
- `meta git checkout .` - Revert all modified files to their remote status.
- `meta git clean -fd` - Remove unwanted untracked files on all repos
