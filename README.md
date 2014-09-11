# Basic Mac Setup

Based on https://github.com/thoughtbot/laptop

## The basics

```sh
curl https://raw.githubusercontent.com/renuo/laptop.local/master/laptop.local > .laptop.local
# Manually install XCode from the app store (old: #xcode-select --install)
sudo xcodebuild -license
bash <(curl -s https://raw.githubusercontent.com/thoughtbot/laptop/master/mac) 2>&1 | tee ~/laptop.log
```

## Install MacVim

```sh
brew install macvim
```

## Adjust .zshrc

https://github.com/renuo/laptop.local/blob/master/zsh_additions.sh
