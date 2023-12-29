`essence.vim` is a 16 colors dark theme for Vim and NeoVim, with low contrast and made with nature-based colors.

* Current optimizations:
    * `markdown`
    * `tex` (with [lervag/vimtex](https://github.com/lervag/vimtex) syntax)

# Colors

* color 00 (black):      `#262626`
* color 01 (red):        `#e14141`
* color 02 (green):      `#87af87`
* color 03 (yellow):     `#e1d741`
* color 04 (blue):       `#87afd7`
* color 05 (magenta):    `#af87d7`
* color 06 (orange):     `#ea9c80`
* color 07 (white):      `#d0d0d0`
* color 08 (dark gray):  `#2b2b2b`
* color 09 (brown):      `#af875f`
* color 10 (green 2):    `#7be141`
* color 11 (yellow 2):   `#d3a800`
* color 12 (blue 2):     `#87afaf`
* color 13 (magenta 2):  `#b6b3eb`
* color 14 (mid gray):   `#464646`
* color 15 (light gray): `#808080`

# How to use

1. Prepare your terminal: 
    * If you are using Vim, configure your terminal to set the colors above. If you are using Neovim, this is optional.
2. Add the colorscheme:
```bash
# For Vim
    git clone https://github.com/yxm-dev/essence.vim && \
    cp essence.vim/colors/essence.vim $HOME/.vim/colors
# For NeoVim
    git clone https://github.com/yxm-dev/essence.vim && \
    cp essence.vim/colors/essence.vim $HOME/.config/nvim/colors
```
3. Set the colorscheme:
```bash
# For Vim
    echo "colorscheme essence" >> $HOME/.vim/vimrc
# For NeoVim
    echo "colorscheme essence" >> $HOME/.config/nvim/init.vim
```

# License

This project is under MIT license.
