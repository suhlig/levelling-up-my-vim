---
title: Levelling Up my Vim
papersize: a4
...

extracted from https://dn.ht/intermediate-vim/

## Inserting

* `I` to insert at the start of the line.
* `o` to start inserting on a new line below the current one.
* `O` to insert above the current line.

## Moving

* `w` and b for moving forward and back a word at a time.
* 'e' move to the end of the previous word
* `fa` move (f)orward to the character (a)
* `52gg` jump to line 52

## Deleting

* `db` to Delete previous word
* `dw` to Delete next word
* `v` to Edit the current command in your text editor (readline in vim mode)

## Editing

* `cw` change word
* `cc` change the entire line — Tip: dd deletes the line
* `ciw` change inside word
* `ci(` change in parenthesis
* `ci{` change in curly brace
* `ci<` change in < > angle brackets
* `ci"` change inside quotes (this leaves the quotes intact)
* `ca"` change (a)round quotes … means quotes get replaced too
* `cat` change (a)round (t)ag … yep, vim understands html tags!
* `ctrl-a` increase number under cursor
* `ctrl-x` decrease number under cursor

## Changing Text

* `~` to change the case of the underlying char

## Vim Surround

https://github.com/tpope/vim-surround

* `cs"'` change surrounding " to '
* `ysiw{` surround with {
* `ds"` remove the delimiters

