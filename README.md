# nerdtree-ag

## Introduction

ag\_path is a [NERDTree](https://github.com/scrooloose/nerdtree)
plugin that adds a menu item to search for a keyword or regex under the
selected path using [ag.vim](https://github.com/rking/ag.vim).

## Installation

### Pathogen

Use the following commands:

    cd ~/.vim/bundle
    git clone https://github.com/mortonfox/nerdtree-ag.git

### Vundle

Add the following to your vimrc:

    Plugin 'mortonfox/nerdtree-ag'

Install with ```:PluginInstall```.

### Manual Installation

Copy ```ag_path.vim``` to ```~/.vim/nerdtree_plugin/``` (*nix)
or ```~/vimfiles/nerdtree_plugin``` (Windows).

## Usage

In the NERDTree window, select the desired folder and then type ```m```
and ```g```. Enter a keyword or regex at the prompt to get a quickfix list of
ag.vim search results.
