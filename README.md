# Mkdir

> Maggie! Don't even ask. Just bring it. Come on.

*-- Hot Rod*

## Installation

Add `pbrisbin/vim-mkdir` to your preferred [vim plugin management plugin](https://linuxhandbook.com/install-vim-plugins/) list.

I happen to use lua configuration and [minpac](https://github.com/k-takata/minpac), so my `~/.config/nvim/init.lua` contains,

```lua
vim.cmd [[ packadd minpac ]]

vim.call('minpac#init')
vim.call('minpac#add', 'pbrisbin/vim-mkdir')
```

## Usage

```
:e this/does/not/exist/file.txt
:w
```

Smile when you are not presented with an error. Instead, notice that 
vim has automatically created the non-existent directory for you.
