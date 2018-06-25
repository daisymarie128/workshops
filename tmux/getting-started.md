# Getting started with tmux

## What is tmux?
Tmux has been described as a screen multiplexer. This basically means that it will let you tile your window panes in a command-line environment.
But what are the benifits of using tmux? Well it allows you to run and keep and eye on multiple programs within one terminal.


Some benifical use cases for using tmux are when you need to access remote servers where you have a common layout that you always use and want to quickly jump in and out of.


Using tmux with Vim also give you a more IDE like feel being able to have access to your shell ennvironment in the same window.


## Installation
This is an installation guide for MacOS only.

Firstly make sure you have `Homebrew` installed.

If you don't see here for more details before moving onto the next step: [Installing Homebrew](https://brew.sh/)

Next you st need to run this in your terminal:
```
brew install tmux
```

Confirm its installed by running
```
tmux -V
```

And boom you've got tmux!

Head here for a list of getting started commands: [Let's learn some basic commands for tmux!](basic-commands.md)
