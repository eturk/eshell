# eshell

A simple shell.

## Requirements

- Loads `PATH` and `HOME` from the file `profile` in the current working directory and throws an error if the file does not exist or either variable is not declared
- Prompt is the current working directory followed by a `>`
- When a user types a command and hits enter, the shell reads the input
  - The first word on the line is the name of the program to run, and the rest should be the arguments to pass that program
	- The command should be found within the `PATH`
- When the program completes, the user is presented with the prompt again
- Handle assignment of `HOME` and `PATH` from the command line
