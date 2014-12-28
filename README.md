# This project is depreciated. It is no longer maintained and should only be used for reference.

# dot-vim

My vim config files

# Usage

Start by cloning the repository and all of it's submodules down to the local system correctly.  Make sure to use the `--recursive`` option.  Git submodules are in use, and to avoid extra work you can have all the submodules download their respective projects in one fluid motion.

```
git clone --recursive https://github.com/svpernova09/dot-vim.git ~/.vim
```

Run bin/install.sh to backup your current settings and install the new .vimrc

```
sudo chmod +x ~/.vim/bin/install.sh && sh ~/.vim/bin/install.sh
```

If you want to remove these settings and restore your original:

```
sudo chmod +x ~/.vim/bin/uninstall.sh && sh ~/.vim/bin/uninstall.sh
```
