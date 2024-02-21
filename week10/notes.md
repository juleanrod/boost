
# [Week10](https://youtu.be/h9giUXQ16To)

### How do I customize Vi/Vim?

Vi and Vim are both text editors, with Vim being an enhanced version of Vi.

Vi stands for "Visual Editor" and is a classic Unix text editor that is typically found on most Unix systems. It has basic functionality for editing and navigating text files.

Vim, which stands for "Vi IMproved," is an improved and more feature-rich version of Vi. It offers additional features such as syntax highlighting, auto-indentation, split-screen editing, and more customization options.

When it comes to configuration files (conf), Vi uses a simple configuration file called ".exrc" or ".vimrc" (for Vim compatibility), where users can define custom settings and key mappings. Vim, on the other hand, allows for more extensive customization through its "vimrc" file, which can contain more advanced settings, plugins, and custom scripts.

In summary, Vim is an enhanced and more customizable version of Vi, with more features and options for configuration

### What is the difference between Vi and Vim?

Vi is a text editor that is the standard editor for Unix-based systems. It is a minimalistic editor with basic features for editing text files.

Vim, on the other hand, is an advanced version of Vi with additional features and enhancements. Vim stands for "Vi Improved" and includes more functionality and customization options compared to Vi. Vim is highly customizable and supports syntax highlighting, plugins, and other advanced features.

In summary, Vim is an enhanced and more feature-rich version of Vi.

### What is VimScript and should I learn it?

VimScript is the scripting language used in the Vim text editor. It allows users to customize and automate tasks within Vim, such as creating custom commands, key mappings, and plugins.

Whether or not you should learn VimScript really depends on your usage of Vim. If you are a heavy Vim user and find yourself frequently customizing and extending Vim's functionality, learning VimScript could be very beneficial. It can help you become more efficient and productive in using Vim.

However, if you only use Vim occasionally and are satisfied with its default
features, you may not need to learn VimScript. It ultimately comes down to your
individual needs and preferences.

### What goes into .vimrc and what does it do?

The .vimrc file is a configuration file used by the Vim text editor. It contains settings and customizations that control the behavior and appearance of Vim.

Some common things that can be included in the .vimrc file are:
- Key mappings: Customize keyboard shortcuts for various commands
- Plugins: Install and configure plugins to enhance functionality
- Theme settings: Change the color scheme and appearance of the editor
- Syntax highlighting: Customize how different programming languages are highlighted

By editing the .vimrc file, users can tailor Vim to meet their specific needs and preferences, making it a powerful and versatile text editor.

### How do I download files from the internet from the command line?

By using `curl` with specific flags to customize its behaviour.

### What is the .vim directory used for?

The .vim directory is used for storing configuration files and plugins for the Vim text editor. Users can customize their Vim environment by adding plugins, themes, and other configurations in this directory. This allows for extended functionality and personalization of the Vim editor.

### How can I add coding language support (Go, Python, bash, etc.)?

To add coding language support in Vim for languages like Go, Python, and bash, you can use plugins specifically designed for each language. Here's how you can add support for these languages:

1. Go:
   - Install vim-go by following the instructions on the GitHub page: https://github.com/fatih/vim-go
   - This plugin provides syntax highlighting, auto-completion, and many other features for Go programming in Vim.

2. Python:
   - Install vim-python by following the instructions on the GitHub page: https://github.com/vim-python/python-syntax
   - This plugin provides syntax highlighting and indentation support for Python code in Vim.

3. Bash:
   - Install vim-bash-support by following the instructions on the GitHub page: https://github.com/vim-scripts/bash-support.vim
   - This plugin provides syntax highlighting, auto-completion, and other features for bash scripting in Vim.

You can install these plugins using a plugin manager like Vundle, Pathogen, or Vim-Plug. Once installed, you should have enhanced language support for Go, Python, and bash in Vim. Remember to read the documentation of each plugin to learn about its features and how to use them effectively.

