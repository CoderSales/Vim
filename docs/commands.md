## commands
### copy and paste a whole line in vim:
Ctrl + V - Enter Visual Block Mode
yy       - Copy line
down     - Move cursor
P        - Put (Paste line)


- `Make sure you're in the normal mode. Press Esc to be sure. Then copy the entire line by pressing yy (more info :help yy ). · Paste the line by ...` [How to copy and paste a line in Vim?](https://www.vimfromscratch.com/articles/how-to-copy-and-paste-a-line-in-vim)
- `This will select the entire line.
Press CTRL+V to enter visual block mode.
Move your cursor to the end of where you want to copy or cut.
Press y to copy. Press d to cut.
Move the cursor to where you want to paste your selection.
Press P (uppercase) to paste before your cursor.
` [Copy & Paste in Vim / Vi](https://www.warp.dev/terminus/vim-copy-paste)

-------------------------------------------

### Move
#### `fx`/`Fx` to occurrence
`fx` - jump to `next` occurrence of character x
`Fx` - jump to the `previous` occurrence of character x

#### `0`/`$` start / end of line
`0` - jump to the start of the line
`$` - jump to the end of the line

#### `%` to matching character
`%` - move to matching character (default supported pairs: '()', '{}', '[]' - use :h matchpairs in vim for more info)
