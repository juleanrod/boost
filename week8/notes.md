# Week 8

### What terminal editors are available for UNIX/Linux?

`ed`, `ex/vi`, `vim`, `nano/pico/joe`, `emacs`

### How to vim (i know some vim already so only adding new commands)

To go back to where you came from press  CTRL-O  (Keep Ctrl down while
pressing the letter o).  Repeat to go back further.  CTRL-I goes forward.

Type  %  to find a matching ),], or } .  

During normal mode, type `!!` and this will change to command mode at the bottom
of the screen inserting `.!#<Enter>` wich means:
 - `.`take the current line the cursor is currently on top of as input
 - `!`to the following external command
 - `#`replace with the bash external command
 - `<Enter>` to execute the external commmand and insert the output replacing
 the current line
    - so if we had, the following line:
    ```sh
    for i in {1..20}; do echo $i.; done
    ```
    this would replace the line with the output of the for loop on the SAME
    file.EPIC
    - REMEMBER: This works on languages that can be interpreted such as; python,
    bash, perl, ruby.

Change to lower case `gu<motion>`   
Change to upper case `gU<motion>`
Go to last character in current line `g_`
If need to look for a command that starts with for example, the letter e, then
you want to start the command -> `:e` + <CTRL+d>

Can use visual mode to highlight text and apply the magic want to that set of
lines; for ex:
    - highlight a bunch of lines
    - followed by the magic want `:!`
    - followed by an external command like `nl` to number the lines
    highlighted.
