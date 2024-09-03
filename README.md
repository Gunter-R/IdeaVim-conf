# IdeaVim-conf
## Introduction
The goal of this config is to reduce mouse usage inside JetBrains IDEs by binding most used actions such as `Run` or `RenameElement` to vim-like combinations.

This config binds only a fraction of possible IDE actions that seem most used to me. If your workflow differs from mine significantly, you will have to add your own bindings.

**Disclaimer1:** this config is currently in the earliest stages of development.

**Disclaimer2:** config has only been tested on Linux.

## Installation
1. Install IdeaVim and Which-Key plugins in your JetBrains IDE
2. Copy contents of `.ideavimrc` from this repository into your `.ideavimrc`
3. Restart your IDE

## Usage
### IDE vs VIM
Some shortcuts that are used by this `.ideavimrc` file are handled by IDE by default (and not by IdeaVim plugin).

To fix this issue, go `Setting > Editor > VIM` and make sure that following shortcuts are handled by Vim:
| Shortcut     	|
| ---------------- |
| `Ctrl` + `H`/`L`  	|

### Shortcuts
IdeaVim extension has a huge limitation: all the vim bindings are available only IN EDITOR. That is, you will have to revert to IDE bindings if some other window (like a file tree or a terminal) is currently selected.

For this reason, I recommend adding some custom IDE shortcuts as well. These are my favorites:

| Shortcut	  | Action                                    	| Usage                               	|
| ----------- | ------------------------------------------- | ------------------------------------- |
| `Alt` + `I` | `Main menu > File > File Open Action > New` | Use in file tree to create a new file |
