# How to restore ssh
- Copy `id_rsa` and `id_rsa.pub` file to `~/.ssh` folder
- Run:
```
sudo chmod 600 ~/.ssh/id_rsa
sudo chmod 600 ~/.ssh/id_rsa.pub
```

# Homebrew
## Install Homebrew
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

## Get Homebrew-Cask
```
brew tap caskroom/cask
```

## Install macOS apps
```
brew install google-chrome
brew install 1password
brew install alfred
brew install sourcetree
brew install visual-studio-code
brew install slack
brew install vlc
brew install scroll-reverser
```

# ZSH
## Install oh-my-zsh:
```
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

# z command:
```
brew install z
```

Add the following to .zshrc:
```
. /usr/local/etc/profile.d/z.sh
```
# Auto-suggestion for zsh
```
brew install zsh-autosuggestions
```

Add the following to .zshrc:
```
source /usr/local/share/zsh-autosuggestions/zsh-autosuggestions.zsh
```
# Cocoapods:
```
brew install rbenv
```

Add the following to .zshrc:
```
eval "$(rbenv init -)"
```

Then restart terminal.

Install Ruby version
```
rbenv install 2.5.1
```
Sets the global version of Ruby
```
rbenv global 2.5.1
```

Install CocoaPods
```
gem install cocoapods
```

# Node:
```
brew install node
```

## n - Node version management:
```
npm install -g n
cd /usr/local
sudo mkdir n
sudo chown -R $(whoami) /usr/local/n
n latest
n lts
```

# React Native:
```
brew install watchman
npm install -g react-native-cli
```
