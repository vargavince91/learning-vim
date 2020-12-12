# learning-vim

This repository includes all the things I learned about Vim.

I am learning Vim as I would like to be a more efficient worker, and so far, using Vim also makes coding fun again.

I found that in order to learn Vim and use it more effectively, one has to learn and configure so many things, that I decided to write everything down as I go along and learn Vim.

As this document contains the things **I** read and learned, I do not currently accept outside contributions (except typo and grammar fixes).

## Why people hesitate to learn Vim?

* a beast that needs to be tinkered with and correctly configured, and constantly reconfigured (as you discover need for more customizations)
* strange keybindings that don't always make sense
* model system is nothing like you've ever used, it makes Vim very different from other editors
* steep learning curve

## Why is it great?

* installed by default on every Unix operating systems
* on servers, remote computers, Vim might be the only option for text editing
* very powerful tool, worth learning the ins and out, you can manipulate texts with few key strokes
* open-source and gets continuously better
* it's been around for a long time so it's easy to find resources

## Get started

* [Vim Adventures](https://vim-adventures.com/) ([solutions](https://github.com/pepers/vim-adventures))
* `vimtutor`: takes around half an hour, it is recommended to go through it multiple times.

Modal editor

Why is Vim a "modal" editor? Because it has modes! Normal, Insert, Visual. When in doubt, stay in Normal (that's why it's called normal).

## keys

* `i` go to insert mode
* `I` insert mode (ignore spaces)
* `s` delete character undor the cursor and change to insert mode
* `S` delete line and change to insert mode
* `O` create new line after current line and change to insert mode
* `o` create new line before current line and change to insert mode
* `cw` delete word and go to insert mode
* `c$` delete from cursor until the end of the line and change to insert mode
* `C` delete from cursor until the end of the line and change to insert mode
* `y` yank
* `yy` yank line
* `yw` yank word
* `p` put (for example yanked stuff)
* `%` jump to matching parenthesis
* `/` search
* `/something<Enter>` + `n` - search for something... jump to next
* `/something<Enter>` + `N` - search for something... jump to previous
* `?` reverse search
* `Control o` - go back to previous position
* `Control i` - go back to previous position
* `h`, `j`, `k`, `l` - basic navigation (left, down, up, right)
* `gh`, `gj`, `gk`, `gl` - move by visual lines (in case of line-wrap)
* `gg` - to the top of the document
* `G` - last line of the document
* `0` - first character of the line
* `^` - first non-space character of the line
* `8G` - jump to eighth line
* `x` - delete character under cursor
* `u` - undo
* C r redo
* `ZZ` - quit
* `dw` - delete word
* `w` - move by word
* `W`, `E`, `B` - same as w, e, b but ignores commas, parenthesis, etc...
* `ft` - forward to character t
* `Ft` - backward to character t
* `tt` - forward to before character t
* `Tt` - backward to after character t
* `!ls` execute command (in this example the ls command)

# To dos

* remap Esc to caps lock
* map ii to leave insert mode


# Resources

Here is a list of all the resources I used.

* [YouTube DistroTube The Vim Tutorial - Part One - Basic Commands](https://www.youtube.com/watch?v=ER5JYFKkYDg)
