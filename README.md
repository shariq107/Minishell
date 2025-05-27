# Minishell
MiniShell is a lightweight, custom implementation of a Unix shell written in C. It mimics the basic functionalities of common shells like Bash, allowing users to execute commands, manage processes, and interact with the system using a simple command-line interface.

📌 Objective
To understand and implement core shell concepts such as:

Command parsing and execution

Process creation and management

Redirection and piping

Signal handling

Built-in shell commands

🛠️ Features
🔹 Execute basic shell commands (e.g., ls, echo, cat)

🔹 Built-in commands: cd, exit, pwd, clear, etc.

🔹 Redirection: >, <, >>

🔹 Pipelines: |

🔹 Environment variable handling (e.g., $PATH, $HOME)

🔹 Signal handling for Ctrl+C, Ctrl+D

🔹 Error handling and custom prompts

🧱 Technologies Used
C Programming Language

POSIX system calls (fork, execve, pipe, dup2, wait, etc.)

Linux environment
