# Tether

A personal desktop hub in the style of VS Code, for Windows: your Obsidian vaults, task backlogs, projects and GitHub repositories, your bookmarks and your feeds in one window.

This repository holds the releases only.

## Install

1. Download `Tether_<version>_x64-setup.exe` from the [latest release](https://github.com/RagedUnicorn/tether/releases/latest).
2. Run it. It installs for your user under `%LOCALAPPDATA%\Tether` and needs no administrator rights.
3. The installer isn't code-signed yet, so Windows SmartScreen warns once: choose "More info", then "Run anyway".

Tether runs the git installed on your machine. Without one it says how to install it (`winget install Git.Git`).

## Updates

An installed copy checks for a newer release when it starts, and on Help › Check for updates. Updates are signed; tether installs only those signed with its own key. Your settings in `~/.tether` stay as they are.

## License

MIT
