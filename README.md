# dotfiles
To run on a new machine:

```
git clone --bare https://github.com/colleenjoy/dotfiles.git $HOME/.dotfiles.git/

git --git-dir=$HOME/.dotfiles.git/ --work-tree=$HOME checkout

$HOME/.config/dotfiles/setup
```

