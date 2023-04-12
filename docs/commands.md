## commands<br>
### copy and paste a whole line in vim:<br>
Ctrl + V - Enter Visual Block Mode<br>
yy       - Copy line<br>
down     - Move cursor<br>
P        - Put (Paste line)


- `Make sure you're in the normal mode. Press Esc to be sure. Then copy the entire line by pressing yy (more info :help yy ). · Paste the line by ...` [How to copy and paste a line in Vim?](https://www.vimfromscratch.com/articles/how-to-copy-and-paste-a-line-in-vim)<br>
- `This will select the entire line.<br>
Press CTRL+V to enter visual block mode.<br>
Move your cursor to the end of where you want to copy or cut.<br>
Press y to copy. Press d to cut.<br>
Move the cursor to where you want to paste your selection.<br>
Press P (uppercase) to paste before your cursor.<br>
` [Copy & Paste in Vim / Vi](https://www.warp.dev/terminus/vim-copy-paste)

-------------------------------------------

### Move<br>
#### `fx`/`Fx` to occurrence<br>
`fx` - jump to `next` occurrence of character x<br>
`Fx` - jump to the `previous` occurrence of character x

#### `0`/`$` start / end of line<br>
`0` - jump to the start of the line<br>
`$` - jump to the end of the line

#### `%` to matching character<br>
`%` - move to matching character (default supported pairs: '()', '{}', '[]' - use :h matchpairs in vim for more info)
