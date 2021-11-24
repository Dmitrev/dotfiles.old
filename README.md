# My Dotfiles
 Collection of my personal dotfiles

 This repo asumes you are on MacOS
 
# Requirements

## [Homebrew](https://brew.sh) - MacOS Package Manager

Install command

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

## [RCM](https://github.com/thoughtbot/rcm) - Managing dotfiles (symlinks)

```
brew install rcm
```


# Installation

Clone repo:

```
git clone git@github.com:Dmitrev/dotfiles.git ~/.dotfiles
```

Sync dotfiles

To dry run:

```
lsrc
```

Do sync:

```
rcup -v
```
