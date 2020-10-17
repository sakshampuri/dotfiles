# All the important configuration files

### .zshrc

All the config for configuring the zshell with oh-my-zsh plugin

-   [oh-my-zsh](https://github.com/ohmyzsh)
-   Theme : [PowerLevel10k](https://github.com/romkatv/powerlevel10k)

Following are the plugins currently added:
plugins=(git zsh-syntax-highlighting brew gitignore vi-mode iterm2 node thefuck npm zsh-autosuggestions extract)

-   Setup Screenshot:
    ![screenshot](https://i.imgur.com/1ndCoWl.png)

### coc-settings.json

This contains all the current configuration for the coc plugin and prettier config according to current project support with es-lint

### init.vim

Neovim configuration

-   Plugin Manager
    [Vim-Plug](https://github.com/junegunn/vim-plug)

All the subsequent plugins can be found inside the config file within the `call plug#begin('~/.vim/plugged')` section

-   Current nvim setup screenshot (TypeScript with expo workflow)
    ![SS](https://i.imgur.com/NorUKHM.png)
