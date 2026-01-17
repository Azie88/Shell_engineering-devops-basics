# Shell Redirections & Filters

In this section, you will learn how to manipulate the input and output of commands.

## Redirections (The arrows)

Normally, commands print to your screen. Redirection lets you send that text somewhere else.

- **`>` (Overwrite)**: Saves the output to a file. Warning: it deletes the old file content!
  - Example: `echo "Hello" > file.txt`
- **`>>` (Append)**: Adds the output to the end of a file (keeps old content).
  - Example: `echo "World" >> file.txt`
- **`<` (Input)**: Feeds a file into a command.

## Pipes ( The `|` symbol )

The pipe `|` takes the output of the command on the left and gives it to the command on the right.
- Example: `ls | grep "my_file"` (List files, then search for "my_file" in that list).

## Common Filters

Filters are commands that take text and transform it:
- `head`: Shows the first few lines.
- `tail`: Shows the last few lines.
- `grep`: Searches for a specific word or pattern.
- `sort`: Sorts lines of text.
