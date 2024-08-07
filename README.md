# NOTE
This is just a fork with some minor tweaks and mappings changed to my liking.

# vim-docker-tools
![demo](https://i.imgur.com/CM7RI6Z.gif) 
* Open DockerTools Panel with `:DockerToolsOpen`, close it with `:DockerToolsClose`
* Toggle DockerTools Panel with `:DockerToolsToggle`
* Set Docker daemon host with `:DockerToolsSetHost`
* Support container commands (and more in the future!). For details please check out the documentation (`:help docker-tools-commands`).
* Autocompletion for commands
* Full documentation in `:help vim-docker-tools`

# Install
* Pathogen

      git clone https://github.com/kkvh/vim-docker-tools.git ~/.vim/bundle/vim-docker-tools

* Vim-plug
```vim
Plug 'kkvh/vim-docker-tools'
```

* NeoBundle
```vim
NeoBundle 'kkvh/vim-docker-tools'
```

* Lazy
```lua
{
    'kkvh/vim-docker-tools',
},
```

* Vundle
```vim
Plugin 'kkvh/vim-docker-tools'
```
* Manual
```sh
git clone git@github.com:messatsuu/vim-docker-tools.git ~/.vim
```

# Roadmap
* [x] Refactor docker runner structure
* [x] Refactor key mapping
* [x] Support custom key mapping
  * [x] Update vim documentation
* [x] Support key mapping with options
* Container functions
* Image functions
* [x] Image command autocomplete
* Network functions
* [x] Network command autocomplete
* Dockerfile functions

# Contributing
Feel free to raise any questions/issues/comments. Submit pull request as you want.
