vim-armasm
==========

## About
Fork of [vim-script#888](http://www.vim.org/scripts/script.php?script_id=888).

This plugin provides syntax highlighting for ARM assembly language.
It includes V2, V3, V4, V5, T, E, M, XS, and VFP extensions, but no V6 or T2 syntax.
It is based on Aleksandar Veselinovic's PIC16F84 Assembler syntax file (pic.vim in the standard installation).

## Authors
Original author: [Gerald Williams](http://www.vim.org/account/profile.php?user_id=1843)

Merged contributions from existent github repos:
* [nviennot/vim-armasm](https://github.com/nviennot/vim-armasm)
* [chazy/vim-armasm](https://github.com/chazy/vim-armasm)
* [scottferg/armasm.vim](https://github.com/scottferg/armasm.vim)

## Installation
Copy to $HOME/.vim/syntax or $VIM/vimfiles/syntax.
Open a buffer with ARM assembly source, and run:

     :call SetSyn("armasm")

You may want to consider adding the following to your .vimrc as well:

     let asmsyntax='armasm'
     let filetype_inc='armasm'

