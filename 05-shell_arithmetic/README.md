# Shell Arithmetic

Shell arithmetic allows you to perform mathematical operations within scripts.

## Concepts
*   **Arithmetic Expansion**: `$(( ... ))`. The preferred mathematical method.
    *   Example: `result=$(( 5 + 3 ))`
*   **let**: Built-in command for arithmetic.
    *   Example: `let result=5+3`
*   **expr**: Legacy command (older, less efficient).
    *   Example: `result=$(expr 5 + 3)` (Spaces required!)

## Operators
*   `+` (Add), `-` (Subtract)
*   `*` (Multiply), `/` (Divide)
*   `%` (Modulus/Remainder)
*   `**` (Exponentiation)

## Resources
*   [Bash Manual - Shell Arithmetic](https://www.gnu.org/software/bash/manual/html_node/Shell-Arithmetic.html)
