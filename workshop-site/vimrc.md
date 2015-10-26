**Q: What is "vimrc"?**

A: The vimrc file is what you use for permanently changing settings.

**Q: How do I use it?**

A: It's literally just a series of `:` commands that get run when you start
Vim. Put whatever you want in it. One command per line, and the `:` is
optional. Lines that start with `"` are comments.

**Q: Sounds good, where is my vimrc file?**

A:

- [Windows][vimrc-location-windows]
- [Not Windows][vimrc-location]

**Q: What are some good things to start off my vimrc with?**

A:

Vim is, by default, set to be backwards-compatible with its 1976 ancestor
vi. Unfortunately, this means a lot of its default settings are really
weird. I won't get into it, but having this setting is just a
universally-accepted Good Idea.

    set nocompatible

Show in-progress commands:

    set showcmd

Show current line and column number:

    set ruler

Show a nice little status bar:

    set laststatus=2

Show line numbers:

    set number

Turn on syntax highlighting:

    syntax on

Finally, the escape key is really important in Vim, and really far away! You
might want to use a mapping or two to make this easier.

(What's a mapping? `:imap x yz` means that whenever you press `x` in insert
mode, Vim will act like you pressed `yz`. So you know, you usually want
`:inoremap`, which is non-recursive. See `:help key-mapping` or any of various
online resources for more.)

Here's one example of a pair of mappings you can use to make getting out of
insert mode easier. (On a standard QWERTY keyboard, this is really good,
because you can just hit j and k with your index and middle fingers.)

    inoremap jk <Esc>
    inoremap kj <Esc>

[vimrc-location-windows]: http://superuser.com/questions/86246/where-should-the-vimrc-file-be-located-on-windows-7
[vimrc-location]: http://stackoverflow.com/questions/10921441/where-is-my-vimrc-file

