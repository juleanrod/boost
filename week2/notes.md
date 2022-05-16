## This lecture covered

- What is UNIX and Linux?
- What is GNU? Who invented Linux?
- What is a "shell" and why do I care?
- What is the difference between a "terminal", "CLI", and "Shell"?
- What is REPL (Read, Evaluate, Print, Loop)
- Install and configure terminal software (MS Terminal, iTerm2)
- What is an "inode"? Why everything is "just a file"?
- How do we install software?
- What is a package?
- How do I know `apt` packages are safe? 

## Package managers (pm)

- All distros have a package manager, we will focus on learning 'apt' pm.
- NOTE: **Never use 'apt' on a script... use 'apt-get'. Refer to 'man apt' to learn more**

## tty's (Teleprinters sometimes referred as teletypes)
- Devices that send or receive written transmissions over a wire or over radios.
- What you call “tty” is actually called “virtual terminal”. A “tty” is actually a character device that represents a connection to ANY kind of terminal, be it an old teletype, a newer CRT-based terminal, a Linux virtual terminal or a terminal emulator.
- By default theres 6 `virtual terminals`, you can acces them by using ctrl+alt+[f[1-6]]
## Commands Used

- man [command]  - show manual for the provided command 
- sudo - do it as root(superuser)
- apt - use interactively only use apt-get in scripts
- sudo apt update - update all the sources for packages
- apt search 'query' - search for packeges you want to
- sudo apt upgrade - upgrade *all* packages to latest version
    - is good practice to take a snapshot of your system before upgrading.
- 'cd -' - change to previous directory
- 'sudo apt remove [package]' - remove a package but not all of it dependencies
- 'sudo apt autoremove' - automatically remove unused packages
- 'sudo apt autoremove --purge [package]' - remove a package with all its dependencies and configuration files

## Resources

- https://www.linuxcommand.org
- intro to the `apt` command - https://www.youtube.com/watch?v=ctGpRWCi8QU 
