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

* Insert the following lines in your ~/.bashrc file:
```bash
export PATH="~/bin/highlight:$PATH"
# Optionally, also add these alias to ease auto-complete:
alias highlight-red="highlight red"
alias highlight-green="highlight green"
alias hightlight-blue="highlight blue"
```