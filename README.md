# Todo - Interactive Script Selector

A terminal-based interactive menu for managing and executing scripts with detailed descriptions and image previews. This tool provides an elegant and user-friendly interface to browse, select, and get information about your scripts.

![Todo Script Selector Demo](path_to_demo.gif)

<img width="952" alt="Image" src="https://github.com/user-attachments/assets/f46924ff-f4ce-4a1e-bba4-4c5e57575d45" />


## Features

- 🎨 Colorful and interactive terminal interface
- 🔍 Real-time script search/filtering
- 📝 Detailed script descriptions
- 🖼️ Image preview support for script documentation
- ⌨️ Easy keyboard navigation
- 🎯 Clean and organized script presentation

<img width="811" alt="Image" src="https://github.com/user-attachments/assets/b0533263-5abd-4dd9-801b-b3e06d876825" />


## Prerequisites



### For macOS
```bash
# Install Homebrew if you haven't already
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

# Install required packages
brew install chafa # For image preview support
```

### For Linux
```bash
# Debian/Ubuntu
sudo apt update
sudo apt install chafa

# Fedora
sudo dnf install  chafa

# Arch Linux
sudo pacman -S  chafa
```

## Installation

Use  the script provided - todoinst
```bash
todoinst
```


1. Clone the repository:
```bash
git clone https://github.com/yourusername/todo.git
cd todo
```

3. Create the required directories:
```bash
sudo mkdir -p /opt/4rji/bin
sudo mkdir -p /opt/4rji/img-bin
```

4. Set up your scripts:
- Place your scripts in `/opt/4rji/bin/`
- Create a `README.md` file in `/opt/4rji/bin/` listing your scripts
- (Optional) Add script images in `/opt/4rji/img-bin/` (supports .webp and .png formats)
- (Optional) Create a `descriptions.json` file in `/opt/4rji/bin/` for detailed script descriptions

## Configuration

### README.md Format
Your `/opt/4rji/bin/README.md` should list scripts in this format:
