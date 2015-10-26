# Ubuntu and other Debian-based Linuxes

- **Just type this into your terminal:** `sudo apt-get install vim` (You will
  be prompted for your password.)
- **Once it's done,** you can run Vim by just typing `vim` into your terminal.

If you haven't seen this sort of command before,

- `apt-get` is your package manager, and it allows you to easily install all
  sorts of useful programs.
- `sudo` (which is what asks for your password) is required when doing
  potentially-dangerous things like installing new programs or modifying
  system files.

---

# Mac

- Good news! **Mac ships with Vim included.** It's a slightly out-of-date
  version, but it won't matter for this workshop.
- You can just type `vim` into your terminal.

---

# Windows

- Go to the download page on the official Vim website, which you can find
  [here.][vim-dl-pc]
- It's pretty easy to install.
    - **Download the installer:** Click `gvim74.exe` link in the "PC: MS-DOS
      and MS-Windows" section.
    - **The defaults are pretty good, but:** Make sure "Create .bat files for
      command line use" is checked. This will allow you to type `vim` or
      `gvim` into Command Prompt to open up Vim.

---

# Other

I don't know the specifics for any other OSes, but:

- **The download page:** [Click me!][vim-dl]
- **Obviously, you might also try Googling** for installation istructions for
  your particular OS.
- **If you're on a Linux or Unix** system, you might have Vim installed
  already. Try typing `vim` into your terminal.
- **If that doesn't work,** you might still have some implementation of vi
  (Vim's predecessor) installed. Try typing `vi` into your terminal. If this
  works, you'll be able to do most of the stuff in this workshop, but a few
  things probably won't work.

[vim-dl]: http://www.vim.org/download.php
[vim-dl-pc]: http://www.vim.org/download.php#pc
