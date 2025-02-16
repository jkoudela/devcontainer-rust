# DevContainer for Rust

## Overview

The Dev Container Rust template provides a development environment based on the official `rust:latest` image with additional features and customizations. It includes:

- Rust language support via `rust-analyzer` extension
- Docker client integration (`ms-azuretools.vscode-docker`)
- GitHub Actions support (`github.vscode-github-actions`)
- YAML schema validation (`redhat.vscode-yaml`)
- Dependency management utilities (`fill-labs.dependi` and `tamasfe.even-better-toml`)
- LLDB debugger support (`vadimcn.vscode-lldb`)

## Features and Customizations

The Dev Container template has the following features and customizations:

- Mounts your local `.gitconfig` and `.ssh` directories into the container
- Configures user environment variables (`GIT_AUTHOR_NAME`, `GIT_AUTHOR_EMAIL`, etc.) to match your local settings
- Installs and configures Zsh as the default shell during container creation

## Usage

To use this Dev Container template, you can either:

- Clone this repository and open it in Visual Studio Code with the Remote Development extension installed
- Use the `vscode.devcontainer` URI scheme to open a new workspace with this template directly

Once you have opened the workspace, you should see the following extensions installed:

- Rust Analyzer (rustlang.rust-analyzer)
- Docker Client Integration (ms-azuretools.vscode-docker)
- GitHub Actions Support (github.vscode-github-actions)
- YAML Schema Validation (redhat.vscode-yaml)
- Dependency Management Utilities (fill-labs.dependi and tamasfe.even-better-toml)
- LLDB Debugger Support (vadimcn.vscode-lldb)

## Configuration

The Dev Container template configuration is stored in the `.devcontainer` directory, and includes:

- `devcontainer.json`: defines container settings and features
- `.gitconfig` and `.ssh` files: mounted into the container to enable authenticated Git operations
- `settings.json`: custom settings for VS Code, including Rust Analyzer configuration

To modify the template configuration, you can edit these files directly or use the VS Code Dev Containers extension to manage them.