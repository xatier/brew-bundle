Brew Bundle
===========

My brew bundle collection

Requirements
============

- [homebrew](http://brew.sh/)

- [homebrew-cask](https://github.com/caskroom/homebrew-cask)

- [homebrew-bundle](https://github.com/Homebrew/homebrew-bundle)


Install
=======

- Install [homebrew](http://brew.sh/) first.

- Install brew-cask and brew-bundle

```
brew install caskroom/cask/brew-cask
brew tap Homebrew/bundle
```

Usage
=====

```
# Install formulae in `Brewfile`
brew bundle

# Backup current installed formulae
brew bundle dump

# Cleanup formulae which are not in the `Brewfile`
# try --dry-run first!
brew bundle cleanup --dry-run
brew bundle cleanup
```
