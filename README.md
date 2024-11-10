
# ShieldedAsh's Dotfiles

This is a collection of my dotfiles used on my Framework 16 running Arch Linux

I pray to god I haven't leaked any secrets here

## Requirements
Make sure you have the following packages installed:

### Git
```
pacman -S git
```

### Stow
```
pacman -S stow
```

## Installation

Clone the repository to your home directory

```
$ git clone git@github.com/ShieldedAsh/dotfiles.git
$ cd dotfiles
```

Then use GNU Stow to symlink the dotfiles to your home directory

```
$ stow .
```

## NOTE

A lot of these dotfiles were not specifically edited and configured by me too much, they were auto configured by someone else and then slightly adapted to my preferences (usually changing the theme to Tokyo Night). Therefore, these dotfiles are not explicitly my creation and are not to be seen as such. All original work goes to the respective repository authors
