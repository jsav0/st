# st
my fork of the suckless simple terminal (st)  
![screenshot](http://n0a110w.xyz/img/compress/iseG.png)
Included patches: (2020-01-30)
- external pipe
  - `super + l` : cycle thru, highlight and copy links that are in view  
  - `super + L` : pass links to `urlhandler.sh` and perform action  
  - `super + shift + I` : extract IPv4 addresses in view and query for info (`info_regex.sh` and `ipinfo.sh`)  
- copyurl
- scrollback
- keyboard select (vim keys)
- alphafocus-highlight
- dracula-colors

- keybindings
  - `alt + h/j/k/l` : scroll up/down one line at a time
  - `alt + shift + h/j/k/l` : scroll up/down one page at a time
  - `alt + c` : copy
  - `alt + v` : paste
  - `alt + shift + esc` : enter "vim-like mode" with keyboard select

### INSTALL
`git clone https://github.com/jsav0/st
sudo make install`

