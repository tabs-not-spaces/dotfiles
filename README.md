# dotfiles
home of my macOS dotfiles

# Install
```zsh
ln -s ~/dotfiles/.zshrc ~/.zshrc
ln -s ~/dotfiles/.zprofile ~/.zprofile
ln -s ~/dotfiles/.config ~/.config
ln -s ~/dotfiles/com.mitchellh.ghostty/config $HOME/Library/Application\ Support/com.mitchellh.ghostty/config
```

# Common homebrew packages
```zsh
brew install --cask ghostty
brew install powershell/tap/powershell
brew tap homebrew/cask-fonts
brew install -cask font-cascadia-code
brew install -cask font-cascadia-code-pl
brew install -cask font-cascadia-mono
brew install -cask font-cascadia-mono-pl
brew install oh-my-posh
brew install fzf
brew install zoxide
brew install rust
brew install --cask docker
brew install kubernetes-cli
brew install helm
brew tap hashicorp/tap
brew install hashicorp/tap/terraform
brew install --cask git-credential-manager
brew install git
brew install dot
```