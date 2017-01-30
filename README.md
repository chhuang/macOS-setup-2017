# [SSH keys](https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/) {#ssh-keys}

# .dotfiles {#dotfiles}

```
git clone git@github.com:chhuang/dotfiles.git

```

# [Brew](http://brew.sh/) {#brew}

```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

```

# Zsh {#zsh}

```
brew install zsh zsh-completions
chsh -s /bin/zsh

```

# [Sublime Text](https://medium.com/@stessyco/how-to-sync-your-sublime-text-settings-across-multiple-computers-via-the-cloud-302594a76c52#.bscmqx3d1) {#sublime-text}

```
ln -s “/Users/chh/Dropbox/0-settings/Sublime Text 3” “/Users/chh/Library/Application Support/”

# Make subl work
ln -s "/Applications/Sublime Text.app/Contents/SharedSupport/bin/subl" /usr/local/bin/subl

```

# Antigen {#antigen}

```
brew install antigen

```

# Git {#git}

```
brew install git
brew install diff-so-fancy

```

# Show hidden files {#show-hidden-files}

```
defaults write com.apple.finder AppleShowAllFiles YES
killall Finder
```



