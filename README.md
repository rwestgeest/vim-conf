# Vim configuration of rwestgeest based on Shingara's and my original janus setup

This vim configuration use [vundle
project](https://github.com/gmarik/vundle).

## How install this configuration

1. Clone this project

```
$ git clone git://github.com/rwestgeest/vim-conf.git .vim-conf
```

2. Link the vimrc in vim-conf clone to .vimrc

```
$ ln -s ~/.vim-conf/vimrc ~/.vimrc
```

3. Install Vundle

```
$ git clone http://github.com/gmarik/vundle.git ~/.vim/bundle/vundle
```

Now you can use the vimrc and use Vundle.

You can see all information about how using vundle in their
documentation

# Using ubuntu and vim in terminal

Please note that when using rich color schemes (like railscasts, solarezed or similar) in gnome terminal make sure you add the following in your .bashrc

```
if [ -n "$DISPLAY" -a "$TERM" == "xterm" ]; then
  export TERM=xterm-256color
fi
```

and for tmux:

```
alias tmux="TERM=screen-256color-bce tmux"
```
