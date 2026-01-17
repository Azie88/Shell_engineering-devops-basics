# Shell Variables & Expansions

This section teaches you how to store information and use special symbols in the shell.

## Variables (Storing Info)

Think of a variable as a labeled box where you can keep a piece of text or a number.

- **Creating a variable**: `NAME="Alice"` (No spaces around the `=`).
- **Using a variable**: `echo $NAME` (Put a `$` before the name to open the box).

## Expansions (Magic Symbols)

"Expansion" usually means the shell replaces a symbol with something else *before* running your command.

- **`*` (Wildcard)**: Matches any characters.
  - `ls *.txt`: List all files ending in `.txt`.
- **`~` (Tilde)**: Represents your "Home" directory.
- **`$(( ))` (Arithmetic)**: Does math!
  - `echo $(( 5 + 5 ))` will print `10`.
- **Alias**: A shortcut for a command.
  - `alias ll="ls -l"`: Now typing `ll` runs `ls -l`.
