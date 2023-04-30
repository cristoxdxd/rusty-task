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
3. Build and run the project: `cargo run`. This will download all the dependencies, build the project, and run the CLI help.

## Usage

The CLI interface supports the following commands:

- `add` - Add a new task to your to-do list
- `list` - List all the tasks in your to-do list
- `done` - Remove a task as completed

## Examples

Add a task to your to-do list:

```bash
$ cargo run -- -j example-name.json add "Buy milk"
Added task "Buy milk"
```

List all the tasks in your to-do list:

```bash
$ cargo run -- -j example-name.json list
1. Buy milk
```

Mark a task as completed:

```bash
$ cargo run -- -j example-name.json done 1
Completed task "Buy milk"
```

## License

This project is licensed under the GNU General Public License. You're free to use, modify, and distribute this code as long as you include the original license and copyright notice.
See the [LICENSE](./LICENSE) file for details.
