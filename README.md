# macOS Setup Guide for Frontend

> Phodal HUANG's macOS setup guide.

1. Install Xcode
2. Download Apps (WeChat, JetBrains Toolbox, Adobe Creative Cloud)
3. Install Brews

```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

4. Install brew Casks


```
brew cask install google-chrome
brew cask install iterm2 sublime-text sourcetree alfred
```

JDK

```
brew tap caskroom/versions
brew cask install java8
```

some tools

```
brew install wget nvm gradle git-extras scrcpy coreutils gnu-sed  —with-default-names
```

## NVM

```
curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.34.0/install.sh | bash
```

config

```
export NVM_DIR="${XDG_CONFIG_HOME/:-$HOME/.}nvm"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh" # This loads nvm
```

## ZSH

change shell

```
brew install zsh
chsh -s /bin/zsh
```

### Oh-my-zsh

```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

## Emacs

install

```
brew install emacs --HEAD  --with-gnutls --with-cocoa --with-mailutils  --with-librsvg --with-ctags --without-libxml2 --with-modules --with-imagemagick@6
```

config

```
git clone https://github.com/purcell/emacs.d.git ~/.emacs.d
````

## iOS

```
brew install libimobiledevice carthage --HEAD 
```

## Tools

```
brew cask install cheatsheet
```

## Android

```
export ANDROID_HOME=/Users/fdhuang/Library/Android/sdk
export PATH=$PATH:$ANDROID_HOME/tools:$ANDROID_HOME/platform-tools
```

## Markdown

1. Download [MacTex](http://www.tug.org/mactex/mactex-download.html)

```
brew install pandoc make
```
