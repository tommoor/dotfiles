# dotfiles

Scripts and dotfiles for getting start on a new machine quickly


## Installation


Install [rcm](https://github.com/thoughtbot/rcm)
```
brew tap thoughtbot/formulae
brew install rcm
```

Install dotfiles
```
git clone git://github.com/tommoor/dotfiles.git ~/.dotfiles
env RCRC=$HOME/.dotfiles/rcrc
rcup
```

Run rcup to update from `~/.dotfiles > ~/` at any time
```
rcup
```


You can now install other essentials from the Brewfile with:

```
brew tap homebrew/bundle
brew bundle
```
