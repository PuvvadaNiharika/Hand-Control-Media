# Hand-Control-Media

# HCI_Project

## Overview
The **HCI_Project** is a Python-based project set up in a version-controlled environment using Git. This project is configured with an integrated development environment (IDE), likely IntelliJ IDEA or PyCharm, to manage dependencies, modules, and virtual environments efficiently.

## Project Structure

- `.idea/`: This directory contains IDE-specific configuration files.
  - `HCI_Project.iml`: Module file for the project.
  - `inspectionProfiles/profiles_settings.xml`: Configuration for inspection profiles.
  - `misc.xml`: Miscellaneous IDE settings.
  - `modules.xml`: Configuration related to project modules.
  - `vcs.xml`: Version control settings.
  - `workspace.xml`: User-specific IDE workspace settings.

- `.venv/`: This is the virtual environment folder where the Python dependencies are stored. This folder is excluded from version control.

## Dependencies

- **Python SDK**: The project is configured to use **Python 3.10**, and the SDK is linked as `Python 3.10 (HCI_Project)` within the IDE settings.
- **Virtual Environment**: The project uses a virtual environment stored in `.venv`. This helps to isolate the project dependencies from the global Python environment.

## Version Control

- **Git**: The project is configured to use Git for version control, as indicated by the `VcsDirectoryMappings` component in the `.idea/` configuration files. This ensures that project changes are tracked effectively.

## Key Features

- **Selective AutoImport**: The project is configured with selective auto-import settings, ensuring that only relevant imports are managed automatically.
- **Project-Specific Profiles**: The project does not use a project-specific inspection profile but inherits the default settings.
- **Task Management**: The project contains a built-in task management system where tasks can be created and tracked.

## IDE Configuration

- **Project Module**: The module configuration for the project is stored in the `HCI_Project.iml` file. This file contains settings related to the module's content, such as source directories and excluded folders.
- **Inspection and Code Analysis**: Inspection profiles are managed via `InspectionProjectProfileManager`. The project is set to use a shared profile rather than a project-specific profile.
- **JDK Configuration**: The project is linked to an inherited JDK configuration, although the primary focus is on the Python SDK.
  
## Getting Started

### Prerequisites

- **Python 3.10** or higher must be installed on your system.
- An IDE like IntelliJ IDEA or PyCharm is recommended for working with the project due to the `.idea/` configurations.

### Setup

1. **Clone the Repository**:
   ```bash
   git clone <repository-url>


pip install -r requirements.txt


python3 -m venv .venv
source .venv/bin/activate

python -m venv .venv
.venv\Scripts\activate

pip install -r requirements.txt

python <script-name>.py

pipenv install --dev
pipenv shell

## Installation Using `setup.py`

### Prerequisites

- **Python 3.10 or higher**
- **Git**

### Installation Steps

1. **Clone the Repository**:
   ```bash
   git clone <repository-url>
   cd HCI_Project

python setup.py install

pip install -r requirements.txt

python -m <module-name>

## Detecting the Language Used in the Project

If you're unsure about the language used in a specific file, you can use the `file` command on Linux or macOS to detect the file type:

1. Open your terminal.
2. Run the following command to detect the language of a specific file:
   ```bash
   file <filename>

file script.py
# Output: script.py: Python script, ASCII text executable


### Option 4: IDE Language Detection with `.editorconfig`

```markdown
## Language Detection Using `.editorconfig`

The project includes an `.editorconfig` file that defines the coding style for different file types in the project. Many IDEs such as VS Code, PyCharm, and IntelliJ IDEA can automatically detect the language and apply the correct formatting based on this file.

### Example `.editorconfig`:
```ini
# EditorConfig helps maintain consistent coding styles
root = true

[*]
indent_style = space
indent_size = 4
charset = utf-8
trim_trailing_whitespace = true
insert_final_newline = true

[*.py]
python_version = 3.10







