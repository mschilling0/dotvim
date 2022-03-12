# dotvim

## Installation

The goal of this repository is two make the base vim configuration usable and
as easy to install as possible.

```command-line
cd $HOME
git clone --recurse-submodules --depth=1 https://github.com/mschilling0/dotvim.git .vim
```

The `vimrc` present is mostly based on this https://github.com/amix/vimrc

Check the `.gitmodules` file for list of plugins that will be installed by
default.

### coc.nvim

If you want to use coc.nvim for fuller-featured VIM plugins, run the
install-coc-nvim.sh script and follow the directions in the script.
(Spoilers, it requires node/npm to be installed on your system.)

https://github.com/neoclide/coc.nvim

If you don't have node/npm installed, consider using nvm.
https://github.com/nvm-sh/nvm

Requires VIM version >= 8.0
