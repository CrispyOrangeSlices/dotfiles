# How to Sync Dots
Use this command inside the dotfiles directory

```bash
cp -r dots/.* ~/
```

## Setup github
- Github CLI 
- Setup SSH, GPG Keys

## Neovim Configuration
- Install packer on the target machine

https://github.com/wbthomason/packer.nvim#quickstart

- source the Packer configuration
```bash
cd ~/.config/nvim/lua/orange/
nvim packer.lua
```

Within Neovim, Ignore all the errors and run these: 
```vim
:so 
:PackerSync
``

