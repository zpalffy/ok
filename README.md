
# ok
A very simple clone of my favorite command line utility that works well with [Oh My Zsh](https://ohmyz.sh/).  See [this post](https://secretgeek.net/ok) for the original inspiration.

> A `.ok` file holds a bunch of handy one-liners, specific to the folder it is in. It can be viewed or executed with a simple command. It makes you smarter and more efficient.

## Installation
1. Clone this repository, or simply [grab the `ok` file](https://raw.githubusercontent.com/zpalffy/ok/refs/heads/main/ok) and put it somewhere on your system.
2. [Source the `ok` file](https://opensource.com/article/20/6/bash-source-command) from your profile, e.g. I have `. ~/ok` in my `~/.zshrc` file.

## Usage
1. Create a `.ok` file in any directory you choose.  Fill it with any commands you use often or just want to remember.  See the included `.ok` file in this repo for some ideas.
2. Run the `ok` function in that directory to get a list of your saved commands
3. Run `ok #` to invoke any of those commands

## Demo
![Demo usage](./demo.svg)

## Customize
Feel free to change the colors or the command prompt that is echoed back when running a command.  See the first few lines in the `ok` file for easy customizations.