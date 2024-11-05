---
title: "Configuring A Modern Macbook For Development"
date: "2024-11-05"
tags: ["reference", "technical", "macOS"]
---

#Configuring A Modern Macbook For Development

Something like this:

```sh
install xcode
install xcode utilities

#Using zsh - generate the environment variable and interactive shell configuration files
$ touch ~/.zshenv    
$ touch ~/.zshrc 
$ source ~/.zshenv 
$ source ~/.zshrc 

#Install nvm
$ curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.0/install.sh | bash

#If needed, kick nvm to wake it up
$ source ~/.nvm/nvm.sh

#Install latest desired node
$ nvm install 22

#Install yarn if you feel like it
$ npm install --global yarn
```

#Happy puppy!