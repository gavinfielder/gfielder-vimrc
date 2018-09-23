# gfielder-vimrc
.vimrc and .vimrc-debug files that I use. The debug file shows tabs, trailing spaces, and end-of-line. Useful while norminette is down.

To use the .vimrc file, place .vimrc in your home directory. Vim will read this file every time it loads.

To use the .vimrc-debug file, use the vim command:
```
:source YOUR_PATH/.vimrc-debug
```
Where YOUR_PATH is, of course, wherever you put the .vimrc-debug file.

You could instead rename the .vimrc-debug to .vimrc and put that in your home folder if you want to show tabs, trailing spaces, and eol by default, if you prefer.
