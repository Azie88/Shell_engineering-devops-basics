# Shell Signals & Processes

Understanding processes and signals is vital for managing running applications and scripts.

## Concepts
*   **PID (Process ID)**: A unique identifier for every running process. `$$` is the PID of the current shell.
*   **Signals**: Notifications sent to processes.
    *   `SIGINT` (Ctrl+C): Interrupt signal.
    *   `SIGTERM`: Termination signal (polite kill).
    *   `SIGKILL` (`kill -9`): Forced termination.
*   **Trap**: Catches signals to perform cleanup or execute code before exiting.
*   **Background Jobs**: Running a command with `&` puts it in the background.

## Resources
*   [Bash Manual - Signals](https://www.gnu.org/software/bash/manual/html_node/Signals.html)
