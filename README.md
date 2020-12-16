# My Nvim

My personal configurations for nvim 

## Installation

After installing [nvim](https://github.com/neovim/neovim/wiki/Installing-Neovim), go to  `~/.config` folder and  clone the project:

```
https://github.com/noreng-jg/nvim
```

You'll need to install vim-plug plugin manager, by running:

```bash
curl -fLo ~/.config/nvim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```
After that open `nvim`, and install the required dependencies by running:

`:PlugInstall`

You could also install the coc-dependencies as listed in `coc-dependencies` file using:

`:CocInstall "dependency"`
