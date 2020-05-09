# base16-cmus

## Info

Base16 for the cmus theme format. Relies on your shell colors also being the same so
make sure to use this in conjuction with [base16-xresources] or [base16-iterm2] or
whatever is the right template for the terminal emulator you have.

[base16-xresources]: https://github.com/chriskempson/base16-xresources
[base16-iterm2]: https://github.com/martinlindhe/base16-iterm2

Cmus color display is a little borked, so the colors from 8 - 15 aren't actually taken
from the shell color pallete, they are just bold/brighter (depending on terminal
emulator) versions of 0 - 7. You can see the relevant source code [here].

[here]: https://github.com/cmus/cmus/blob/d1290d50f9f7585c43b9e1326c0d6d1e0b4583f6/ui_curses.c#L1780

## Install

Put into `~/.config/cmus`.
