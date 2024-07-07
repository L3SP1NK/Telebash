# Telebash

Telebash is a Bash script that allows you to send messages using Telegram. It provides a convenient way to interact with the Telegram Bot API from the command line. With Telebash, you can send text messages or even send documents to your desired chat.

## Setup

1. Clone the Telebash repository from GitHub: [Telebash GitHub Repo](https://github.com/L3SP1NK/Telebash)
2. Make the script executable: `chmod +x telebash`
3. Obtain a Telegram Bot Token from [@botfather](https://t.me/botfather) on Telegram.
4. Create a file named `telebash_token.txt` in the `~/.config/telebash/` directory.
5. Paste your Telegram Bot Token into the `telebash_token.txt` file and save it.

## Usage

To use Telebash, run the script with the following command:


### Options

- `-d, --document <path>`: Send a document.
- `-f, --favorites`: Show your favorite chat IDs.
- `-h, --help`: Display the help menu.
- `-t, --text <text>`: Send a text message.
- `-u, --update`: Get the latest updates from Telegram (groups, messages, etc.).

To get a chat ID, you can run the script with the `--update` option.

## Notes

- Telebash uses the Telegram Bot API, and it supports the parsing modes "html" and "markdown" for formatting text messages.

- Telebash provides an interactive and convenient way to interact with Telegram using your command line.

For more information and updates, please visit the [Telebash GitHub repository](https://github.com/yourusername/telebash).

Enjoy using Telebash to send messages with Telegram!
