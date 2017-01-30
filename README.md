# [SSH keys](https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/) {#ssh-keys}

# .dotfiles {#dotfiles}

```
git clone git@github.com:chhuang/dotfiles.git
```

# [Brew](http://brew.sh/) {#brew}

```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

# Mac App Store

```
brew install mas
mas signin email@email.com
```

# Brewfile {#zsh}

```
ln -s "/Users/chh/.dotfiles/Brewfile" "/Users/chh/"
```

```
brew 'git'
brew 'node'
brew 'npm'
brew 'diff-so-fancy'
brew 'antigen'
brew 'zsh' 
brew 'zsh-completions'

cask 'iterm2'
cask 'docker'
cask 'dropbox'
cask 'gitkraken'
cask 'flux'
cask 'google-chrome'
cask 'spectacle'
cask 'spotify'
cask 'insomnia'
cask 'gitter'
cask 'appdelete'
cask 'sublime-text'

mas 'Slack', id: 803453959
mas 'Alfred', id: 405843582
```

```
brew bundle install
```

# Zsh {#zsh}

```
chsh -s /bin/zsh
```

# [Sublime Text](https://medium.com/@stessyco/how-to-sync-your-sublime-text-settings-across-multiple-computers-via-the-cloud-302594a76c52#.bscmqx3d1) {#sublime-text}

```
ln -s "/Users/chh/Dropbox/0-settings/Sublime Text 3" "/Users/chh/Library/Application Support/"

# Make subl work
ln -s "/Applications/Sublime Text.app/Contents/SharedSupport/bin/subl" /usr/local/bin/subl
```

# Show hidden files {#show-hidden-files}

```
defaults write com.apple.finder AppleShowAllFiles YES
killall Finder
```



