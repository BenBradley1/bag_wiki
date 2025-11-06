# Vim Cheat Sheet

Here are some useful vim shortcuts I've compiled.

## Why use Vim?
Vim is a free, open-source text editor accessed via the command line. It is old but very powerful—there's a reason it's stuck around!

## Cheat sheet

---
### Navigation

#### Document

`gg` : go to the first line

`G` or `:$` : go to the end

`5gg` or `:5` : go to line 5

#### Pages

`Ctrl` + `f` : move forward one page

`Ctrl` + `b` : move backward one page

`Ctrl` + `u` : move up half a page

`Ctrl` + `d` : move down half a page

`H` : move to top of screen

`M` : move to middle of screen

`L` : move to bottom of screen

#### Cursor

`zz` : centre screen on cursor

`zt` : move screen so cursor is at top

`zb` : move screen so cursor is at bottom

#### Lines

`home` or `0` : jump to start of line

`end` or `$` : jump to end of line

---
### Editing

#### Cut and Yank (Paste)

`yy` : yank a line

`5yy` : yank 5 lines

`yaw` : yank a word, copy the word under the cursor and spaces before or after

`p` : paste after cursor

`P` : paste before cursor

#### Replace

`r` : replace a single character

`R` : replace multiple characters until `Esc` pressed

#### Insert

`i` : insert mode

`o` : open a new line below the current line

`Esc` : exit insert mode

---
### General

`.` : repeat last command

`u` : undo

`/pattern` : search for _pattern_
