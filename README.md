# dotfiles

1. Install [brew](https://brew.sh/).

2. Install git.

```brew install git```

3. iTerm [Setup](https://gist.github.com/kevin-smets/8568070)

4. nvm [Setup](https://github.com/creationix/nvm)

4. SSH [setup](https://help.github.com/articles/connecting-to-github-with-ssh/)

5. Clone repository to hidden .dotfile directory in your home directory

```git clone git@github.com:evarouss/dotfiles.git ~/.dotfile```

6. Run setup-symlinks.sh

```source ~/.dotfiles/setup-symlinks.sh```

7. Install Software part 1 (brew)

```source ~/.dotfiles/setup-brew.sh```

8. Symlink VSCode stuff.

VSCode:
```
ln -s /Users/evarouss/.dotfiles/VSCode/settings.json ~/Library/Application\ Support/Code/User/settings.json
ln -s /Users/evarouss/.dotfiles/VSCode/keybindings.json ~/Library/Application\ Support/Code/User/keybindings.json
```

9. Install VSCode plugins

```source ~/VSCode/install-plugins.sh```

10. Install Software part 2 (App Store)

* Things
* Slack
* Tweetbot
* Patterns
* Xcode

11. Profit