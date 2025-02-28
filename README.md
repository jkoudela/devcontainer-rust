# Rust DevContainer Template

## Overview

This repository provides a template for setting up a Rust development environment using VS Code Dev Containers. It's based on the official `rust:latest` Docker image and comes pre-configured with essential extensions and tools for Rust development.

## Features

- 🦀 Rust toolchain with cargo and rustup
- 📝 Rust-Analyzer for intelligent code completion and analysis
- 🐛 LLDB debugging support
- 🐋 Docker integration
- 🔧 Git configuration and SSH key forwarding
- 💻 Zsh shell with custom configuration
- 📦 TOML and dependency management support

## Included VS Code Extensions

- `rust-analyzer` - Rust language support
- `vadimcn.vscode-lldb` - Debugging support
- `ms-azuretools.vscode-docker` - Docker integration
- `github.vscode-github-actions` - GitHub Actions support
- `redhat.vscode-yaml` - YAML support with schema validation
- `tamasfe.even-better-toml` - Enhanced TOML support

## Getting Started

1. Ensure you have the following prerequisites installed:
   - Visual Studio Code
   - Docker Desktop
   - VS Code Remote Development Extension Pack

2. To use this template:
   - Click "Use this template" on GitHub to create a new repository
   - Clone your new repository
   - Open in VS Code
   - When prompted, click "Reopen in Container"

## Container Configuration

The development container is configured in the `.devcontainer` directory:

- `devcontainer.json` - Container configuration and features
- Custom VS Code settings optimized for Rust development
- Git and SSH configuration forwarding from host

## Customization

To customize the development environment:

1. Modify `.devcontainer/devcontainer.json` to:
   - Add or remove VS Code extensions
   - Change container settings
   - Add additional tools or dependencies

2. Update VS Code settings in `.devcontainer/settings.json`

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This template is available under the MIT License. See the LICENSE file for more details.