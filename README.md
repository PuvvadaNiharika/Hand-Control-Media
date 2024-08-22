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
