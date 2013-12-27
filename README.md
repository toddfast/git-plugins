git-plugins
===========

An expanding collection of git plugins I find useful.


## Installation

1. Clone the repository to your local machine
1. Run `chmod +x git-*` in the repository root directory
1. Change your `PATH` to include the repository root directory (e.g. on Max OS X, in `~/.bash_profile` add `export PATH=$PATH:<repository root>`)
1. Use the commands anywhere you use git, i.e. `git <command>`


## Commands

### git ahead [--graph] [other git log parameters]

Determines what the "commit difference" is between your local branch and it's upstream copy (adapted from http://zanshin.net/2013/01/25/git-log-command-showing-commit-differences-between-local-and-remote-repository/).


## Writing your own git plugins

See http://adamcod.es/2013/07/12/how-to-create-git-plugin.html