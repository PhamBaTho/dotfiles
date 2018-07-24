# ZSH
## Install Zsh
brew install zsh

## Set Zsh as your default shell:
chsh -s /bin/zsh

## Make Zsh active
source ~/.zshrc

# Homebrew
## Install Homebrew
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)" </dev/null
brew update

## Get Homebrew-Cask
brew tap caskroom/cask

## Install macOS apps
brew cask install google-chrome
brew cask install 1password
brew cask install dropbox
brew cask install alfred
brew cask install sourcetree
brew cask install visual-studio-code
brew cask install slack
brew cask install vlc

# Others:
## Setup z command:
- Install with brew:
brew install z
- Put the following line in $HOME/.zshrc:
. /usr/local/etc/profile.d/z.sh
