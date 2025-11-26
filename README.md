# AstroNvim Template

**NOTE:** This is for AstroNvim v4+

A template for getting started with [AstroNvim](https://github.com/AstroNvim/AstroNvim)

## 🛠️ Installation

#### Make a backup of your current nvim and shared folder

```shell
mv ~/.config/nvim ~/.config/nvim.bak
mv ~/.local/share/nvim ~/.local/share/nvim.bak
mv ~/.local/state/nvim ~/.local/state/nvim.bak
mv ~/.cache/nvim ~/.cache/nvim.bak
```

#### Create a new user repository from this template

Press the "Use this template" button above to create a new repository to store your user configuration.

You can also just clone this repository directly if you do not want to track your user configuration in GitHub.

#### Clone the repository

```shell
git clone https://github.com/<your_user>/<your_repository> ~/.config/nvim
```

#### Start Neovim

```shell
nvim
```
#### A few words to the uninitiated

If you are installing from Windows you may need to create the nvim directory yourself.  It should be located in your AppData directory, as nvim points out in the initial help file.

You also may need to run this in powershell, and/or a custom shell like [alacritty](https://github.com/alacritty/alacritty).

You also may need to install a gcc compiler to get treesitter to work [like in this thread](https://www.reddit.com/r/neovim/comments/14oozmu/neovim_cant_find_c_compiler/).  
