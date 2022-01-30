# Eureka Module

This repo is an example of a Eureka Module. A Eureka Module is simply a Git Submodule containing Markdown files with extended support for the Obsidian Wikilinks Syntax.

Each module should have atleast a `README.md` explaining about its dependencies.

## Getting Started

1. Create new git repository to host your eureka module
2. `git clone --bare git@github.com:TongHuaLabs/eureka-module.git`
3. `cd eureka-module.git`
4. `git lfs fetch --all`
5. `git push --mirror https://github.com/exampleuser/new-repository.git`
6. `git lfs push --all https://github.com/exampleuser/new-repository.git`
7. `cd .. && rm -rf eureka-module.git`

## Dependencies

If a Eureka Module has links to other Eureka Modules, list them here.
