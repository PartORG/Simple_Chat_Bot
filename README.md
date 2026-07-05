# Simple_Chat_Bot

A simple CLI Chat Bot written in Python to help you with basic tasks and conversations.

[![Python](https://img.shields.io/badge/python-3.6%2B-blue.svg)] [![License](https://img.shields.io/badge/license-MIT-green.svg)] [![GitHub stars](https://img.shields.io/github/stars/PartORG/Simple_Chat_Bot?style=social)] [![GitHub forks](https://img.shields.io/github/forks/PartORG/Simple_Chat_Bot?style=social)]

## Introduction

Simple_Chat_Bot is a lightweight command-line interface (CLI) chat bot designed to assist with basic tasks and engage in conversations. It's perfect for anyone looking for a simple, easy-to-use tool to interact with their computer or automate repetitive tasks.

The primary workflow of Simple_Chat_Bot involves running the script from the command line and interacting with it through text-based commands and responses. Its main advantages include its simplicity, ease of use, and the ability to be easily extended with new features.

## Features

### Basic Task Automation
- **Execute Commands**: Run simple shell commands directly from the bot.
- **Fetch Information**: Retrieve system information or perform quick searches.

### Conversational Interaction
- **Engage in Chats**: Have a basic conversation with the bot for fun and interaction.
- **Help Requests**: Get assistance with common questions and tasks.

## How It Works

Simple_Chat_Bot is built using Python and follows a straightforward architecture. The main entry point of the application is `main.py`, which handles user input, processes commands, and generates responses.

Here's a simplified overview of how it works:

1. **User Input**: The bot reads user input from the command line.
2. **Command Processing**: It parses the input to determine the intended action.
3. **Response Generation**: Based on the command, the bot generates an appropriate response.
4. **Output**: The response is displayed in the command line.

## Technology Stack

| Technology | Purpose |
|------------|---------|
| Python     | Main programming language for building the chat bot. |
| Shell      | Used to execute system commands and retrieve information. |

## Requirements

- Python 3.6 or higher
- No additional dependencies required

## Installation

To install Simple_Chat_Bot, simply clone the repository:

```bash
git clone https://github.com/PartORG/Simple_Chat_Bot.git
```

Then navigate to the project directory and run the script:

```bash
cd Simple_Chat_Bot
python main.py
```

## Configuration

Simple_Chat_Bot does not require any external configuration files or environment variables.

## Quick Start

To get started with Simple_Chat_Bot, simply clone the repository and run the script as described in the Installation section. Once running, you can interact with the bot by typing commands into the command line.

Example:

```bash
$ python main.py
Welcome to Simple_Chat_Bot!
Type 'help' for a list of available commands.
> help
Available commands:
- execute <command>
- fetch <info>
- exit

> execute ls -la
total 0
```

## Usage

Here are some example commands you can use with Simple_Chat_Bot:

- **Execute Commands**:
  ```bash
  > execute echo "Hello, World!"
  Hello, World!
  ```

- **Fetch Information**:
  ```bash
  > fetch uptime
  Uptime: 1 day, 2 hours, 30 minutes
  ```

## Project Structure

```
Simple_Chat_Bot/
├── README.md
└── main.py
```

- `README.md`: This file you're reading.
- `main.py`: The main entry point of the chat bot.

## Development

Simple_Chat_Bot is a simple project, so there's not much to develop. If you want to add new features or improve existing ones, feel free to fork the repository and submit a pull request.

## Testing

No tests are currently available for Simple_Chat_Bot.

## Limitations

- **Basic Functionality**: The bot is designed for basic tasks and conversations.
- **Limited Commands**: Currently supports only a few commands. More features can be added as needed.

## License

Simple_Chat_Bot is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.