# Reloaded License

This project contains the licenses used by the Reloaded project, including rationale/FAQ behind each license and the corresponding license text.

**View the documentation at:** [https://reloaded-project.github.io/License/][github-pages]

## Documentation

MkDocs documentation for the Reloaded-Project/License project.

Open the project folder in VSCode as your workspace for documentation editing.

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

## Quick Start (Recommended)

From the project root directory:

```bash
python3 start_docs.py
```

This script will:
- Create a virtual environment if needed
- Install all required dependencies
- Start the MkDocs live server at http://127.0.0.1:8000

The documentation will be available at http://127.0.0.1:8000 (paste into browser address bar). Press Ctrl+C to stop the server.

For more detailed contributing guidelines, see [Contributing Guide][contributing-guide]

[github-pages]: https://reloaded-project.github.io/License/
[python-org]: https://python.org/
[python-downloads]: https://python.org/downloads/
[contributing-guide]: https://reloaded-project.github.io/Reloaded.MkDocsMaterial.Themes.R2/Pages/contributing.html
