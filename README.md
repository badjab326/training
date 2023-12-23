# Installfest

Follow these instructions to set up your laptop for work in SEI. If you've previously set up a development environment on your computer, you may wish to skip some of these steps; do not do so without first checking with an consultant!

If at any point you are unsure of whether you have done something correctly, ask a consultant. It's important in many cases that we do these steps in order. In general, if you receive no output, the command has executed successfully. (No news is good news.) If you receive output in your terminal that you didn't expect, please notify a consultant.

**The goal of this is not for you to fully understand everything that is being set up on your computer or what all of these tools do!** You should be focused on following along and completing the instructions. If you have any specific questions about anything you do today, we will be happy to answer after Installfest is complete.

#### Note for Linux Users

We mainly support macOS and slightly Ubuntu (an open-source Linux based OS) at SEI. If you choose
to use Linux, we strongly recommend using the latest Ubuntu [LTS](https://ubuntu.com/about/release-cycle) (currently 22.04). To Install Linux on Windows with WSL and Set up a WSL development environment follow this link. It is recommended to Install WSL, Set up your Linux username and password, Update and upgrade packages, and Set up Windows Terminal.
[wsl setup](https://learn.microsoft.com/en-us/windows/wsl/setup/environment)
If you choose to use a different Linux distribution, or a different version of Ubuntu, the scripts in this repository
will _not_ work, and you will be responsible for configuring your own development
environment. Only choose this option if you're an experienced Linux user and enjoy
troubleshooting.

| Setup                                                            | Description                                                                    |
| ---------------------------------------------------------------- | ------------------------------------------------------------------------------ |
| [Github and Initial Setup](github.md)                            | Set up accounts for GitHub & GitHub Enterprise. Fork and Clone this repository |
| [Git](git.md)                                                    | Set global Git config, add SSH keys for GitHub & GHE                           |
| [Bash Configuration](bash.md)                                    | Set up necessary bash files                                                    |
| [Command Line Tools - Xcode (macOS only)](command_line_tools.md) | Install Xcode                                                                  |
| [Homebrew](homebrew.md)                                          | Install Homebrew package manager                                               |
| [Node](node.md)                                                  | Install nvm, Node, and global npm packages                                     |
| [Chrome](chrome.md)                                              | Install Chrome and configure settings                                          |
| [VS Code](vscode.md)                                             | Install VS Code/extensions and configure settings                              |
