# Mnimi

Mnimi is a simple Python program to record and display notes and todo items. Lists are stored in a JSON file that can easily be parsed by other utilities.

## Installation

Mnimi requires no special setup. Download the `mnimi` python file, put it somewhere in your `$PATH`, and execute it.

The `mnimi` AUR package can be used to install Mnimi on Arch.  
<https://aur.archlinux.org/packages/mnimi/>

## Usage

When executed with no arguments Mnimi will print the current todo list without extended notes. It can be called with `-n` to create a new todo item, `-r` to remove an existing item, or `-a` to amend an existing item. Call with `-e` to print extended notes and `-h` for help.

## Dependencies

Python >=3.6
