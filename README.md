<div align="center">

# cyanic.nvim

A Neovim colorscheme adapted from [habamax.nvim](https://github.com/ntk148v/habamax.nvim) which itself is ported
from the <a href="https://github.com/vim/colorschemes/blob/master/colors/habamax.vim">Vim Habamax</a> colorscheme.

</div>

## Screenshots

TBA

## Installation

- Using `vim-plug`:

```vim
Plug 'rktjmp/lush.nvim'
Plug 'samuell/cyanic.nvim'
```

- Using `packer`:

```lua
use { "samuell/cyanic.nvim", requires={ "rktjmp/lush.nvim" } }
```

- Using `lazy.nvim`:

```lua
{ "samuell/cyanic.nvim", dependencies={ "rktjmp/lush.nvim" } }
```

## Usage

```vim
colorscheme cyanic.nvim
```

```lua
vim.cmd("colorscheme cyanic.nvim")
```

## Contribution

This colorscheme is always in development and testing. Users are welcome to use
it however for programming daily. In case a user spots any bugs or error
especially related to the supported plugins, treesitter or built-in LSP
highlight support, then they can contribute by opening an issue or by making a
pull request. More plugin highlight support is also welcome.

## Credits

This colorscheme is built with [lush.nvim](http://git.io/lush.nvim); for more
information on Lush and a helper script to setup your repo clone.
