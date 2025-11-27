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
#### A few words to the uninitiated (and Windows users)

If you are installing from Windows you may need to create the ```nvim``` directory yourself.  It should be located in your ```AppData``` directory, as nvim points out in the initial help file.  This will look something like ```C:\Users\<username>\AppData\Local\nvim```.  There may already be a ```nvim-data``` folder present.

Also it's cool to run nvim in Powershell, and/or a custom shell like [alacritty](https://github.com/alacritty/alacritty).  Alacritty can allow certain [themes](https://github.com/alacritty/alacritty-theme) and [fonts](https://alacritty.org/config-alacritty.html#font).  Just make sure you have the most up-to-date java libraires declared in your ```JAVA_HOME``` directory. 

Certain libraries like ```treesitter``` will require a GCC compiler to run.  You may install GCC to get these libraries to work [like this thread](https://www.reddit.com/r/neovim/comments/14oozmu/neovim_cant_find_c_compiler/) or [like in this set of instructions](https://code.visualstudio.com/docs/cpp/config-mingw#_installing-the-mingww64-toolchain) with the download from [MSYS2](https://www.msys2.org/).  

You will also have some problems with Mason.nvim, when you can't download the correct files for ```jdtls```.  It's best to update the ```config.lua``` file located under ```%APPDATA%\Local\nvim-data\lazy\nvim-java\lua\java\config.lua``` and update the version there to the latest available, like ```v1.54.0```, for example.
