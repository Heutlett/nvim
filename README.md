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
4. Install nerd font:
```shell
wget -P ~/.local/share/fonts https://github.com/ryanoasis/nerd-fonts/releases/download/v3.0.2/JetBrainsMono.zip \
&& cd ~/.local/share/fonts \
&& unzip JetBrainsMono.zip \
&& rm JetBrainsMono.zip \
&& fc-cache -fv
```
5. Update the font in your terminal, probably you must update the fonts cache *CLOSE ALL THE TERMINALS* and then go to preferences and select the font `JetBrainsMono Nerd Font Regular`:
```shell
fc-cache -fv
```
7. To enable bidirectional copy install this:
```shell
sudo apt install xsel
sudo apt install xclip
```
Then, to copy just select the text and press `y` and paste with ctrl+v.

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

# Mason:

**Keyboard Shortcuts**

* **g?** — Show help (just type ?)
* **<CR>** — Toggle package information
* **<CR>** — Toggle installation log
* **<C-f>** — Apply language filter
* **i** — Install package
* **x** — Uninstall package
* **U** — Update selected package
* **u** — Update all outdated packages
* **c** — Check for new version (selected package)
* **C** — Check for new versions (all packages)
* **<C-c>** — Cancel package installation
* **q** — Close window
* **<Esc>** — Close window

