# Introduction

This is a reference manual for sgit (Small Git).

Sgit is an easy-to-use CLI tool for git-related commands. It is supposed to bring shortcuts as well and is supposed to be linked to github.

# Requirements

If you are making your own implementation for Sgit, it cannot be named exactly `sgit`. It must be named something else with `sgit` in it, like `johnsgit` or `sgitcool`.
You **cannot** name your `sgit` implementation `sgitwin` or `sgitunix`, since those are the official `sgit`s.

If you want your implementation to be an `sgit`, it is okay to add other things not listed in this speculation as long as you comply the whole spec.

# Installation

Sgit should be installed to the path. Therefore, when you open any directory in the terminal, sgit should be easily accessed by `sgit [commands...]`.

The installer for the Sgit does not matter, as long as it correctly installs Sgit to the path.

The file of Sgit should be named `sgit`, nothing else.

The implementation can put any other requirements they need to put; for example, the user needs a specific version of an application to make sgit work.

## Package Installers

If a package installer is going to be used, then any package installer can be used. It does not matter which package installer is used as long as it works.

# Commands

Each command of sgit will be doing a specific thing. Here are the commands:

* `help`
* `install`
* `clone`

## help

The `help` command is required to show all the commands of sgit and what those commands do. The commands must be descriptive and must be easy to distinguish.

The implementation can put anything else if they'd like to. The `help` command though must be a **help** command, it has to do with helping the user, not doing anything else.

## install

The `install` command is required to install the latest version of `sgit`. The implementation can put anything else they'd like to into the `install` command, but the `install` command **must** install the latest version.

## clone

Not finished.
