# Atom-Latte-lang-IDE
The IDE for Latte-lang on Atom

# How to Use
## Download
Install `Atom-Latte-lang-IDE` in Atom.

or

Download this repository, move it to `~/.atom/packages/` and restart Atom

## Config
If you have `latte` or `latte.bat` in `$PATH` variable, then this configuration can be ignored.

Otherwise, press `CMD + Shift + P`, type `Application: Open Your Config` and press enter.

Add the following configuration

    "atom-latte-lang-ide":
      latte : "latte or latte.bat location"

("atom-latte-lang-ide" should be a key of `"*"`)

## Use
Press `Shift-F9` to run the current script

Press `Shift-F10` to compile all `.lt` files in the project directory

In `Packages - Atom-Latte-lang-IDE` menu, you can click `Generate build.lts & run.lts` to generate the build script.

# What is Latte-lang
Latte-lang is a JVM Language.

![](http://latte.cassite.net/images/highlight.png)

go to [Repository](https://github.com/wkgcass/Latte-lang)

go to [Web Page](http://latte.cassite.net)

# License
The `atom-latte-lang-ide` is based on [atom-shell-commands](https://github.com/skywind3000/atom-shell-commands).  
Check `LICENSE of Atom-Shell-Commands.md`
