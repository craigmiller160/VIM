# VIM Configuration

A backup of my local vim configuration

## Install VIM

```
sudo apt update
sudo apt install vim
```

## Install Vundle

```
git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
```

## Restore Configuration

Copy the `.vimrc` file from this project to the root of your home directory.

## Install Plugins

Open the `.vimrc` file with VIM and then run `:PluginInstall`.

## Setup Terminal Shortcuts

To modify the terminal itself to use VIM shortcuts, add this to the `.inputrc` file (create if doesn't exist)

```
set editing-mode vi
set keymap vi
```
