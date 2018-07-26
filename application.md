# Homebrew
## Install Homebrew
```
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)" </dev/null

brew update
```

## Get Homebrew-Cask
```
brew tap caskroom/cask
```

## Install macOS apps
```
brew cask install google-chrome
brew cask install 1password
brew cask install dropbox
brew cask install alfred
brew cask install sourcetree
brew cask install visual-studio-code
brew cask install slack
brew cask install vlc
```

# ZSH
## Install Zsh
```
brew install zsh
```
## Set Zsh as your default shell:
```
chsh -s /bin/zsh
```

## Install oh-my-zsh:
```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

## Add path for homebrew:
```
echo '# Homebrew
export PATH="/usr/local/sbin:$PATH"' >> ~/.zshrc
```

## Make Zsh active (optional):
```
source ~/.zshrc
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
```
rbenv install 2.5.1
rbenv global 2.5.1
gem install cocoapods
```

# Node:
```
brew install node
```

# n - Node version management:
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
