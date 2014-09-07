# Basic Mac Setup

Based on https://github.com/thoughtbot/laptop

## The basics

```sh
curl https://raw.githubusercontent.com/renuo/laptop.local/master/laptop.local > .laptop.local
sudo xcodebuild -license
xcode-select --install
bash <(curl -s https://raw.githubusercontent.com/thoughtbot/laptop/master/mac)
```

## Install MacVim

```sh
xcode-select --install # choose "Get Xcode"
brew install macvim
```

## Adjust .zshrc

https://github.com/renuo/laptop.local/blob/master/zsh_additions.sh
