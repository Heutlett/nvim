# nvim

# Installation

1. Download the last version of nvim from the oficial website
```shell
sudo add-apt-repository ppa:neovim-ppa/unstable
sudo apt update
sudo apt install neovim
```
2. Install dependencies
```shell
sudo apt-get install ripgrep
sudo apt install python3-venv
```
3. Copy this directory to ~/.config/
6. Install the lsps

# Commands

## Limpia el historial

vim.keymap.set('n', '<leader>h', ':nohlsearch<CR>')

## Treesitter:

<leader> ff = find files
<leader> fg = live grep

## Lsp:

<leader> K = code description
<leader> gd = go to definition
<leader> gD = go to declaration
<leader> gi = go to implementation
<leader> gr = go to references
<leader> rn = rename
<leader> ca = code actions

## Formatting
<leader>gf = format

## Comments:

CTRL + v , shift+i, #, esc

## Neotree:

Activar CTRL + n

Ver ayuda = ?


