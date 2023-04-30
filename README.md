# rusty-task

## **CLI To-Do List Project in Rust**

This is a simple Command Line Interface (CLI) To-Do list project built using Rust. This project is designed to help you learn the basics of Rust and CLI application development.

## Features

- Add tasks to your to-do list
- View your to-do list
- Mark tasks as completed
- Remove tasks from your to-do list

## Requirements

- Rust programming language (minimum version 1.68.2)

## Installation

1. Clone this repository: `git clone https://github.com/cristoxdxd/rusty-task.git`
2. Change to the project directory: `cd rusty-task/`
3. Build the project: `cargo run --release`.
4. Change to the target directory: `cd target/release/`
5. Run the project: `./rusty-task` or `./rusty-task.exe` (Windows)

## Usage

Linux/macOS: `./rusty-task [OPTIONS] <SUBCOMMAND>`
Windows: `./rusty-task.exe [OPTIONS] <SUBCOMMAND>`

The CLI interface supports the following commands:

- `add` - Add a new task to your to-do list
- `list` - List all the tasks in your to-do list
- `done` - Remove a task as completed
- `help` - Display the help menu

## Examples

Add a task to your to-do list:

```bash
$ ./rusty-task add "Buy milk"
Added task "Buy milk"
```

List all the tasks in your to-do list:

```bash
$ ./rusty-task list
1. Buy milk
```

Mark a task as completed:

```bash
$ ./rusty-task done 1
Completed task "Buy milk"
```

## License

This project is licensed under the GNU General Public License. You're free to use, modify, and distribute this code as long as you include the original license and copyright notice.
See the [LICENSE](./LICENSE) file for details.
