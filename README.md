# vim-tips
This are tips and tricks for vim which I found the most usefull, extracted from the official documentation.

## Shortcuts
- insert mode, Ctrl+A : insert previously inserted text
- insert mode, Ctrl+C : quit insert mode
- insert mode, Ctrl+D : delete one shift width of indent on the current line
- insert mode, Ctrl+T : insert one shift wifth of an indent on the current line
- insert mode, Ctrl+E : insert the character that is below the cursor
- insert mode, Ctrl+Y : insert the character that is above the cursor
- insert mode, Ctrl+O : execute a single command and return to insert mode
- insert mode, Ctrl+R <register> : insert the content of a register
- insert mode, Ctrl+U : delete all characters before the cursor on the current line
- insert mode, Ctrl+V <char> : insert next non-digit literally
- insert mode, Ctrl+W : delete word before the cursor
- normal mode ZZ : write buffer and exit
- normal mode Ctrl+A : add N number at the cursor
- normal mode Ctrl+X : substract N number at the cursor
- normal mode Ctrl+G : display current filename and position
- normal mode Ctrl+O : go backward in jump list
- normal mode Ctrl+I : go forward in jump list
- normal mode K : open man page about the word under the cursor, see: keywordprg
- normal mode Ctrl+L : redraw the screen
- normal mode Ctrl+R : redo
- normal mode Ctrl+V : start blockwise visual mode
- normal mode # : search backward next occurrence of word under cursor
- normal mode * : search forard next occurrence of word under cursor
- normal mode / : search forward
- normal mode ? : search backward
- normal mode A : append text to the end of the current line, goes into insert mode
- normal mode C : change the characters after the cursor, goes into insert mode
- normal mode D : delete the characters after the cursor
- normal mode f{char} : cursor to the first next occurrence of {char}
- normal mode F{char} : cursor to the first previous occurrence of {char}
- normal mode t{char} : cursor to the character before the first next occurrence of {char}
- normal mode T{char} : cursor to the character after the first previous occurrence of {char}
- normal mode I : insert text at the beginning of the line, goes into insert mode
- normal mode R : enter replace mode : overwrite exisiting text as typing
- normal mode gf : go to file in current path whose name is under the cursor
- normal mode gi : go to last insert and enter edit mode
- normal mode gx : open url in browser

## Features
- abbreviations
- filter
- read
- macros
