# dotfiles

## Setting up the Pi

Update System

```
sudo apt-get -y update && sudo apt-get -y upgrade
```

Install other packages

1 . Install zsh and other packages
```
sudo apt-get install -y curl wget zsh vim tree nmap tmux git
```

2 . Install oh-my-zsh, copy paste one of these commands:
```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

## This repo has several directories to support multiple platforms

Directory | Purpose
--------- | -------
linix | Linux/UNIX platforms (or compatible)
windows | Windows platform
mac | Mac 