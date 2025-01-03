# 🚀 Airdrop Farming Scripts Premium Channel Guide

Welcome to the premium scripts channel Guide! This guide will help you set up your environment and get started with airdrop farming across different platforms.

## 📋 Table of Contents
- [Prerequisites](#prerequisites)
- [Platform Setup Guide](#platform-setup-guide)
  - [Windows Setup](#windows-setup)
  - [MacOS Setup](#macos-setup)
  - [Linux Setup](#linux-setup)
  - [Termux Setup (Android)](#termux-setup-android)
- [Common Issues & Solutions](#common-issues--solutions)
- [Support & Contact](#support--contact)

## 🔧 Prerequisites

Before running any scripts, ensure you have:
- A stable internet connection
- Access to terminal/command prompt
- Basic understanding of command line operations
- Sufficient storage space (minimum 5GB recommended)
- A Telegram account to access script updates

## 💻 Platform Setup Guide

### Windows Setup

1. **Install Required Software**
   ```bash
   # Install Python
   - Visit python.org/downloads
   - Download latest Python version
   - Run installer (IMPORTANT: Check "Add Python to PATH")
   - Verify installation: open cmd and type "python --version"
   
   # Install Node.js
   - Visit nodejs.org
   - Download LTS version
   - Run installer
   - Verify: "node --version"
   
   # Install Git
   - Visit git-scm.com
   - Download and install Git
   - Verify: "git --version"
   ```

2. **Setup Development Environment**
   ```bash
   # Open Command Prompt as Administrator
   
   # Install Python packages
   pip install web3 python-dotenv requests
   
   # Install Node packages
   npm install -g yarn ethers hardhat
   ```

### MacOS Setup

1. **Install Homebrew First**
   ```bash
   /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
   ```

2. **Install Required Software**
   ```bash
   # Install Python
   brew install python
   
   # Install Node.js
   brew install node
   
   # Install Git
   brew install git
   ```

3. **Setup Development Environment**
   ```bash
   # Install Python packages
   pip3 install web3 python-dotenv requests

   # Install Node packages
   npm install -g yarn ethers hardhat
   ```

### Linux Setup

1. **Update System First**
   ```bash
   sudo apt-get update && sudo apt-get upgrade -y
   ```

2. **Install Required Software**
   ```bash
   # Install Python
   sudo apt-get install python3 python3-pip -y
   
   # Install Node.js
   curl -fsSL https://deb.nodesource.com/setup_lts.x | sudo -E bash -
   sudo apt-get install nodejs -y
   
   # Install Git
   sudo apt-get install git -y
   ```

3. **Setup Development Environment**
   ```bash
   # Install Python packages
   pip3 install web3 python-dotenv requests
   
   # Install Node packages
   sudo npm install -g yarn ethers hardhat
   ```

### Termux Setup (Android)

1. **Initial Setup**
   ```bash
   # Update package list
   pkg update && pkg upgrade -y
   
   # Install required packages
   pkg install python nodejs git openssh -y
   ```

2. **Setup Development Environment**
   ```bash
   # Install Python packages
   pip install web3 python-dotenv requests
   
   # Install Node packages
   npm install -g yarn ethers hardhat
   ```

## ❗ Common Issues & Solutions

1. **Python "command not found"**
   - Windows: Reinstall Python and ensure "Add to PATH" is checked
   - Mac/Linux: Use `python3` instead of `python`

2. **Permission Errors**
   - Windows: Run as Administrator
   - Mac/Linux: Use `sudo` before commands
   - Termux: No sudo needed, but ensure storage permission is granted

3. **Package Installation Fails**
   - Check internet connection
   - Try updating pip: `python -m pip install --upgrade pip`
   - For Node: Clear npm cache: `npm cache clean --force`

## 🔍 Running Scripts

1. Clone the repository:
   ```bash
   git clone https://github.com/Fl3xxRichie/[repository-name]
   ```

2. Install project dependencies:
   ```bash
   cd [repository-name]
   npm install  # For Node.js scripts
   # OR
   pip install -r requirements.txt  # For Python scripts
   ```

3. Follow script-specific instructions in the respective script folders

## 📱 Support & Contact

- Private Channel: [Premium Script](https://t.me/+GIfY4Pb0Spw5OGZk)
- Public Channel: [Airdrop3arn](https://t.me/airdrop3arn)
- Direct Contact: [FlexxRichie](https://t.me/flexxrichie)
- Twitter: [@FlexxRichie](https://twitter.com/FlexxRichie)
- GitHub: [@Fl3xxRichie](https://github.com/Fl3xxRichie)

## ⚠️ Important Notes

1. Never share your private keys or seed phrases
2. Always review scripts before running them
3. Use a separate wallet for farming
4. Keep your system and scripts updated
5. Join the Telegram Public channel for latest updates and support

---

<div align="center">
  <i>Happy Farming! 🌱</i>
</div>