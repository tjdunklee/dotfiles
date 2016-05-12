dotfiles
========

My Personal Set of Config Files that are meant to sit on top of the [space150
dotfiles](https://github.com/space150/dotfiles) and be managed with
[rcm](https://github.com/thoughtbot/rcm).

## Install

First you need to follow clone and install the [space150
dotfiles](https://github.com/space150/dotfiles) that these depend on. Then you can proceed with:

```
cd
cd dotfiles
mkdir tjdunklee
cd
git clone git@github.com:tjdunklee/dotfiles.git dotfiles/tjdunklee/
rcup -d dotfiles/tjdunklee/ -x README.md
```

If you don't have it already, be sure to install Vundle.

```
cd
git clone https://github.com/gmarik/Vundle.vim.git ~/.vim/bundle/Vundle.vim
```

When MacVim is running, make sure to run Vundle to grab all the plugins.

```
:BundleInstall
```

## What's Included

#### [nerdtree](https://github.com/scrooloose/nerdtree)
A tree explorer plugin for vim.  
**Bound to:** `,n`

#### [vundle](https://github.com/gmarik/vundle)
Vundle, the plug-in manager for Vim

#### [ctrlp](https://github.com/kien/ctrlp.vim)
Fuzzy file, buffer, mru and tag finder  
**Bound to:** `,f`

#### [sparkup](https://github.com/rstacruz/sparkup)
A parser for a condensed HTML format.  
**Bound to:** `,e`

#### [nerdcommenter](https://github.com/scrooloose/nerdcommenter)
The premier commenting tool.  
**Bound to:** `c<space>`

#### [ack](https://github.com/mileszs/ack.vim)
Vim plugin for the Perl module / CLI script 'ack  
**Called by:** `:Ack`

#### [indent-guides](https://github.com/nathanaelkane/vim-indent-guides)
A Vim plugin for visually displaying indent levels in code  
**Bound to:** `,ig`

#### [airline](https://github.com/vim-airline/vim-airline)
Mega overhaul of the statusbar, colorized per mode.

