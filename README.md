# Undertakingyou TMUX config

This is my attempt to easily centralize my tmux configuration.

## Setup
* Clone this directory tot he `~/.config/tmux` directory. Example `git clone
    <repository_url> ~/.config/tmux`. Make sure to include the submodules.
* Link the included tmux.conf tot he home directory as a hidden file so that it
    is found at `~/.tmux.conf`
* Link the included tmux-powerline to `~/.config/tmux-powerline`. Note, if you
    do this before the installation of any plugins / the running of tmux, you
    can link the entire directory. If not, that directory will already be made
    and you will need to link the contents.
* Run `tmux`
* Install the plugins with `C-a I`, which will grab any not already included
    plugins.

## System considerations
This works best with [Nerd Fonts](https://github.com/ryanoasis/nerd-fonts). I
really like the Noto Mono version, but whatever you use. This will give a large
list of glyphs.

One configuration change of note, the prefix key has been changed to `C-a`, to
better match screen which I used for many years.
