# Shell Functions

Functions allow you to block code into reusable sections.

## Concepts
*   **Definition**: `function_name () { ... }` or `function function_name { ... }`
*   **Arguments**: Accessed inside the function using `$1`, `$2`, etc. `$0` is still the script name.
*   **Scope**: Variables are global by default. Use `local` keyword for local variables.
*   **Return**: `return` sets the exit status (0-255). To return data, `echo` it.

## Resources
*   [Bash Manual - Shell Functions](https://www.gnu.org/software/bash/manual/html_node/Shell-Functions.html)
