# nvim_settings
personal nvim settings, the end goal is have a script that sets up nvim with these settings and plugins on a brand new machine.

## Installation
Create the nvim initialization directory;
```bash
$ mkdir -p ~/.config/nvim/bundle  // implicitly create the bundle dir and the nvim implicitly
$ cp init.vim ~/.config/nvim
```

Download the repos listed below, then in nvim run `:PluginInstall`

## repos
Below is a list of the nvim plugins I am using. Each should be cloned in the `.config/nvim/bundle` directory.
TODO: Write a script so this download process is automated.

### Vundle
https://github.com/VundleVim/Vundle.vim
```bash
$git clone https://github.com/gmarik/Vundle.vim
```

### gitgutter
https://github.com/airblade/vim-gitgutter
```bash
$$git clone git://github.com/airblade/vim-gitgutter.git
```

### lightline
https://github.com/itchyny/lightline.vim
```bash
$git clone https://github.com/itchyny/lightline.vim
```

### nerdtree
https://github.com/scrooloose/nerdtree
```bash
$git clone https://github.com/scrooloose/nerdtree.git
```

### vim-fetch
https://github.com/wsdjeg/vim-fetch
```bash
$git clone git@github.com:wsdjeg/vim-fetch.git
```
