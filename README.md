
# Advanced Package Manager Project (WIP!)

## Overview
This project simulates an advanced package manager in Python, resembling functionalities of popular package managers like npm or pip. It includes features like dependency resolution, version control, and a sample Python application to demonstrate its usage. I would like to extend its benefits further. 

## Features
- **Dependency Resolution**: Handles complex dependency trees for package installation.
- **Version Management**: Supports installing specific versions of packages.
- **Package Database**: Maintains a local JSON file to track installed packages and their versions.
- **Simulated Remote Repository**: Uses a simulated URL structure for package fetching (not functional in real-world usage).

## Project Structure
- `package_manager.py`: The core script of the package manager handling package operations.
- `advanced_project/main.py`: Main application file demonstrating the package manager usage.
- `advanced_project/config.json`: Configuration file for the application.
- `advanced_project/utils.py`: Utility functions for the application.
- `advanced_project/tests/`: Directory containing unit tests for the application.
- `advanced_project/requirements.txt`: Lists packages to be installed by the package manager.
- `advanced_project/package_db.json`: JSON file acting as a local database for installed packages.

## Installation
To set up the package manager:
1. Clone or download the project repository.
2. Navigate to the `advanced_project` directory.
3. Ensure Python is installed on your system.

## Usage
- **Installing a Package**: `python package_manager.py install <package_name>`
- **Uninstalling a Package**: `python package_manager.py uninstall <package_name>`
- **Listing Installed Packages**: `python package_manager.py list`

## Running the Application
To run the sample application:
1. Navigate to the `advanced_project` directory.
2. Run `python main.py`.

## Testing
Unit tests can be run by navigating to the `tests` directory and executing the test files.

