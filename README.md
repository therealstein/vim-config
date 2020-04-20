
# VIM -config

```
~/
---- .vim/
---- ---- (plugins and stuff)
---- ---- vimrc
```


No need to create symlinks or whatever.

This is how I would push my config on a new machine where Git has already been installed:
```bash
cd ~
git clone --recurse-submodules https://github.com/therealstein/vim-config.git .vim
```

