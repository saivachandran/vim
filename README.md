# vim

From: http://stackoverflow.com/questions/1676632/whats-a-quick-way-to-comment-uncomment-lines-in-vim

For those tasks I use most of the time block selection.

Put your cursor on the first `#` character, press `Ctrl``V` (or `Ctrl``Q` for gVim), and go down until the last commented line and press `x`, that will delete all the `#` characters vertically.

For commenting a block of text is almost the same: First, go to the first line you want to comment, press `Ctrl``V`, and select until the last line. Second, press `Shift``I``#``Esc` (then give it a second), and it will insert a `#` character on all selected lines. For the stripped-down version of vim shipped with debian/ubuntu by default, type `: s/^/#` in the second step instead.
