# Homework5 - Command System

This repository contains a Python project that implements a plugin-based command system for handling user inputs and performing various operations. The goal of this project is to demonstrate the use of classes, functions, and plugins to handle multiple commands dynamically.

## Branch: `commands`

This branch includes the implementation of the command system where different commands can be executed based on user input.

## Features

- **AddCommand**: Adds two numbers provided by the user.
- **Command Plugin System**: Dynamically load and execute commands.
- **Extensibility**: Easy to add new commands by extending the existing plugin system.

## Files

- **`main.py`**: The main entry point of the application where commands are processed.
- **`commands/`**: Contains the individual command classes that handle specific operations (e.g., AddCommand).
- **`test_main.py`**: Contains unit tests for the command system to ensure correctness.

## How to Run

1. **Clone the repository:**
    ```bash
    git clone https://github.com/SamuelSudeepAyyala/Homework5.git
    ```

2. **Navigate to the project directory:**
    ```bash
    cd Homework5
    ```

3. **Switch to the `commands` branch:**
    ```bash
    git checkout commands
    ```

4. **Run the main Python file:**
    ```bash
    python main.py
    ```

5. **Execute a command:**
    The program will prompt for user input. For example, to add two numbers:
    ```
    Enter command: add
    Enter first number: 5
    Enter second number: 3
    Result: 8
    ```

## How to Add New Commands

To add new commands, follow these steps:

1. Create a new Python file in the `commands/` folder.
2. Define a class that implements the command functionality. Ensure it follows the structure of the existing `AddCommand` class.
3. Update the command registry in `main.py` to include the new command.

## Running Tests

To run the tests for this project:

```bash
pytest test_main.py
