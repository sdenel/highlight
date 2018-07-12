# Highlight

A simple python script to highlight text like grep would do, but without filtering lines. The script is compatible with Python 2 and Python 3.

## Exemple

![AN example of using highlight](screenshot.png)

## Installation

To install highlight only for the current user:
```console
mkdir -P ~/bin
cd ~/bin
git clone https://github.com/sdenel/highlight
```

Then insert the following lines in your ~/.bashrc file:
```bash
# Installing highlight tool from https://github.com/sdenel/highlight
export PATH=~/bin/highlight/:$PATH
# Optionally, also add these alias to ease auto-complete:
alias highlight-red='highlight red'
alias highlight-green='highlight green'
alias highlight-blue='highlight blue'
```