# Atelier Forest Color Scheme for Vim

Based on work by Bram De Haan.

![Atelier Forest Dark](http://www.kream.io/files/atelier_forest_640x425.png)

## Installation

### Option 1: vim-plug ***(recommended)***
Download and install Junegunn Choi's [vim-plug].

```vim
Plug 'KarboniteKream/vim-atelier-forest'
```

Check [vim-plug] documentation for more details.

### Option 2: Manual installation
Copy `atelier_forest.vim` to your `.vim/colors` directory.

```bash
$ cp vim-atelier-forest/colors/atelier_forest.vim ~/.vim/colors/
```

### Modify .vimrc
Put the following three lines in your `.vimrc`:

```vim
syntax enable
set background=dark
colorscheme atelier_forest
```

## License

Copyright (c) 2013 - 2017 [Bram de Haan](http://atelierbramdehaan.nl)

Released under [MIT Licence](http://atelierbram.mit-license.org)

[vim-plug]: https://github.com/junegunn/vim-plug
