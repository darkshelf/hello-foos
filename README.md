# hello-foos
Sample repo

Hail and well met worthy traveler, welcome to the hello-foos repo. I don't know what you will find as you explore this repo but once identified an acknowledgement of it's existence will be added here.


## Useful Commands from Day 1

### Show Library folder

```shell
chflags nohidden ~/Library
```

#### Show hidden files

This can also be done by pressing `command` + `shift` + `.`.

```shell
defaults write com.apple.finder AppleShowAllFiles YES
```

### Brew Commands

#### Install Homebrew
```shell
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

#### Brewup
Run - brew update; brew upgrade; brew prune; brew cleanup; brew doctor
```shell
brewup
```

#### Source bash profile
```shell
source ~/.bash_profile
```

#### Install Mac App Store command line
```shell
brew install mas
```

#### Sign into Mac App Store command line
```shell
mas signin [Your Email addy]
```

#### Accept xcode license
```shell
sudo xcodebuild -license
```

#### Terminal Colors

```bash
export PS1="\[\033[36m\]\u\[\033[m\]@\[\033[32m\]\h:\[\033[33;1m\]\w\[\033[m\]\$ "
export CLICOLOR=1
export LSCOLORS=ExFxBxDxCxegedabagacad
```

### Git
#### Set username

```bash
git config --global user.name "darkshelf"
```
