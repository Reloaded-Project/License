# Contributing to License Documentation

This guide covers how to build and edit the documentation locally.

## Prerequisites

**Python 3.7+** is required to build and serve the documentation.

### Installing Python

- **Linux**: Typically pre-installed. If not available, use your package manager:
  ```bash
  # Ubuntu/Debian
  sudo apt update && sudo apt install python3 python3-pip python3-venv
  
  # Fedora/RHEL
  sudo dnf install python3 python3-pip
  ```

- **macOS**: Download from [python.org][python-org] or install via Homebrew:
  ```bash
  brew install python3
  ```

- **Windows**: Run in Command Prompt or PowerShell:
  ```bash
  winget install Python.Python.3
  ```
   Or download manually from [python.org/downloads][python-downloads]

## Quick Start

From the project root directory:

```bash
python3 start_docs.py
```

This script will:
- Create a virtual environment if needed
- Install all required dependencies
- Start the MkDocs live server at http://127.0.0.1:8000

The documentation will be available at http://127.0.0.1:8000 (paste into browser address bar). Press Ctrl+C to stop the server.

## Editing Documentation

Open the project folder in VSCode as your workspace for documentation editing. Documentation files are located in the `docs/` directory.

For detailed contributing guidelines, see the [Reloaded Contributing Guide][contributing-guide].

[python-org]: https://python.org/
[python-downloads]: https://python.org/downloads/
[contributing-guide]: https://reloaded-project.github.io/Reloaded.MkDocsMaterial.Themes.R2/Pages/contributing.html
