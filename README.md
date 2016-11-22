# Atelier Forest Color Scheme for Vim

Based on work by Bram De Haan.

![Atelier Forest Dark](http://atelierbram.github.io/syntax-highlighting/assets/img/forest-dark_vim_640x425.png)

![Atelier Forest Light](http://atelierbram.github.io/syntax-highlighting/assets/img/forest-light_vim_640x425.png)

## Installation

### Option 1: vim-plug ***(recommended)***
Download and install Junegunn Choi's [vim-plug].

```vim
Plug 'KarboniteKream/vim-atelier-forest'
```

Check [vim-plug] documentation for more details.

### Option 2: Manual installation
Copy `base16-atelier-forest.vim` to your `.vim/colors` directory.

```bash
$ cp vim-atelier-forest/colors/base16-atelier-forest.vim ~/.vim/colors/
```

### Modify .vimrc
Put the following three lines in your `.vimrc`:

```vim
syntax enable
set background=dark
colorscheme base16-atelier-forest
```

## License

Copyright (c) 2013 - 2015 [Bram de Haan](http://atelierbramdehaan.nl)

Released under [MIT Licence](http://atelierbram.mit-license.org)

[vim-plug]: https://github.com/junegunn/vim-plug
