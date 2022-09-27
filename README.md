# My LS_COLORS configuration file
This repo contains the dircolors configuration file which I use to colorize file listings within a 256 color capable terminal. It defines the LS_COLORS enviroment variable used by 'ls' to map filetypes to colors. 

## Installation
Copy the dircolors file to your home directory and rename it to .dircolors<br>
Add the following to your Shell's rc file:<br>
eval $(dircolors -b $HOME/.dircolors)

## Reload the Shell or Logout \ Login
source ~/.zshrc<br>
Ctrl+d
