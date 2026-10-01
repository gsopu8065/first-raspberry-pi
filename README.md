# Prerequisites

Before running your first program, complete these setup steps:

- If your microSD card does not already contain Raspberry Pi OS, use [Raspberry Pi Imager](https://www.raspberrypi.com/software/) and follow the setup steps.
- Connect a mouse, keyboard, and monitor.
- Change the keyboard layout from `europe` to `usa`.
- Install `git`, `gh`, `node`, and `npm`.

## Helpful commands

### File and directory navigation

- `pwd`: Prints the current working directory path so you know where you are in the file system.
- `ls`: Lists all files and folders in the current directory. Use `ls -l` for detailed permissions and sizes, or `ls -a` to show hidden files.
- `cd`: Changes the current working directory (for example, `cd folder_name` or `cd ..`).
- `mkdir`: Creates a new folder or directory. Use `mkdir -p folder/subfolder` to create nested paths in one command.
- `touch`: Creates a new empty file or updates the timestamp of an existing file.
- `rm`: Deletes files. Use `rm -r` to remove folders and their contents carefully.

### System and package management

- `sudo`: Runs a command with administrator (root) privileges, which is required for installing software or modifying system files.
- `sudo apt update && sudo apt upgrade`: Updates package lists and upgrades installed software to the latest versions.
- `top` or `htop`: Displays active system processes and real-time CPU and memory usage.
- `df -h`: Shows available disk space in a human-readable format.

### Networking and troubleshooting

- `ping`: Tests network reachability and connection speed to another computer or website.
- `ifconfig`: Displays network interface details, including the local IP address and MAC address.
- `grep`: Searches for specific text patterns inside files or command output.

# Raspberry Pi Hello World

A small Node.js project written in TypeScript and compiled with `tsc`.

## Run it

Install Node.js and npm on the Raspberry Pi, then run the following commands from this directory:

```sh
npm install
npm run build
npm start
```

The program prints `Hello, Raspberry Pi!`. The TypeScript source is in `src/index.ts`, and `tsc` writes the runnable JavaScript to `dist/`.
