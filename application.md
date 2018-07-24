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

## Make Zsh active (optional):
```
source ~/.zshrc
```

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

# z command:
- Install with brew:
```
brew install z
```
- Add the following to .zshrc:
```
. /usr/local/etc/profile.d/z.sh
```

# Auto-suggestion for zsh
- Install with brew:
```
brew install zsh-autosuggestions
```
- Add the following to .zshrc:
```
source /usr/local/share/zsh-autosuggestions/zsh-autosuggestions.zsh
```
