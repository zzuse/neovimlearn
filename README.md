# NeoVim config files

Just for reference, not in use, deprecated, 
Using https://github.com/zzuse/nvim_config.git instead.

## HowTo

```
git clone https://github.com/bigeagle/neovim-config.git
ln -s path/to/neovim-config ~/.config/nvim
curl -fLo ~/.config/nvim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
pip install neovim
```

use [vim-plug](https://github.com/junegunn/vim-plug) to manage my plugins, you can deactive unneeded ones by commenting `~/.config/nvim/init.vim`.

run `nvim` then run `:PlugInstall` 
