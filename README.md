# My neovim

Configurations for neovim.

## Installation

After installing [nvim](https://github.com/neovim/neovim/wiki/Installing-Neovim), go to  `~/.config` folder and  clone the project:

```
git clone https://github.com/noreng-jg/nvim
```

You'll need to install [vim-plug](https://github.com/junegunn/vim-plug) plugin manager, by running:

```bash
curl -fLo ~/.config/nvim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```
After that open `nvim`, and install the required dependencies by running:

`:PlugInstall`

You can also install the coc-dependencies as listed in `coc-dependencies` file using:

`:CocInstall "dependency"`

## Observations
* You might also want to install `yarn` which will help to customize better the coc-extensions.
* For vue development check the [vetur](https://vuejs.github.io/vetur/guide/setup.html) setup.
* In order to use `Bracey` you will need to install a python3 neovim package:
```bash
pip3 install --user neovim
```

