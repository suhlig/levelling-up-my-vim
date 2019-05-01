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
* `fa` move (f)orward to the character (a)
* `52gg` jump to line 52

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

## Vim Surround

https://github.com/tpope/vim-surround

* `cs"'` change surrounding " to '
* `ysiw{` surround with {
* `ds"` remove the delimiters

