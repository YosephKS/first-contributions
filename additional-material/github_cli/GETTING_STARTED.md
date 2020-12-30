# Getting Started

In this tutorial, we will provide all the necessary steps to get started using GitHub CLI. The tutorial will be divided into two arts: Installation and Authentication. Make sure to follow all the steps carefully in order to set up GitHub CLI in you machine successfully.

### Introduction

GitHub CLI is a brand new open-source development tool provided by GitHub in order to have easy access in managing PR, issues, check, releases, and more, through the command line. This tutorial is considered intermediate-advanced, therefore it is assumed that those who follow this tutorial must have prior basic knowledge on Git and GitHub.

### Installation

GitHub CLI is available for repositories hosted on GitHub.com and GitHub Enterprise Server 2.20+, and to install on macOS, Windows, and Linux. Make sure to follow the instructions based on your machine's existing Operating System.

#### MacOS

GitHub CLI is available via Homebrew, MacPorts, and as a downloadable binary from the [releases page](https://github.com/cli/cli/releases/latest).

- Homebrew

|      Install      |      Upgrade      |
| :---------------: | :---------------: |
| `brew install gh` | `brew upgrade gh` |

- MacPorts

|        Install         |                    Upgrade                     |
| :--------------------: | :--------------------------------------------: |
| `sudo port install gh` | `sudo port selfupdate && sudo port upgrade gh` |

#### Windows

GitHub CLI is available via WinGet, scoop, Chocolatey, and as downloadable MSI.

- WinGet

|       Install       |       Upgrade       |
| :-----------------: | :-----------------: |
| `winget install gh` | `winget install gh` |

- scoop

|      Install       |      Upgrade      |
| :----------------: | :---------------: |
| `scoop install gh` | `scoop update gh` |

- Chocolatey

|      Install       |      Upgrade       |
| :----------------: | :----------------: |
| `choco install gh` | `choco upgrade gh` |

- Signed MSI

MSI installers are available for download on the [releases page](https://github.com/cli/cli/releases/latest).

#### Linux

- Debian, Ubuntu Linux (apt)
- Fedora, CentOS, Red Hat Enterprise Linux (dnf)
- openSUSE/SUSE Linux (zypper)

### Authentication

After Installation, it is important to connect to your GitHub account through the authentication process. Run `gh auth login` to authenticate with your GitHub account.

### More Resources

For more resources and in depth explanation, check out GitHub CLI official webiste and repository. Since GitHub CLI is an open-source project, feel free to contribute.

- [GitHub CLI Website](https://cli.github.com/)
- [GitHub CLI Repository](https://github.com/cli/cli)

### Author

For those who have contributed in this README file, feel free to have your names listed here.

- [Yoseph Kurnia Soenggoro](https://github.com/YosephKS)
