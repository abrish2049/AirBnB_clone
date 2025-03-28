# AirBnB Clone

![HolBnB clone](hbnb.png?raw=true)

Welcome to the AirBnB clone project! This project is a simplified clone of the AirBnB platform, built to demonstrate the implementation of a full-stack web application.

## Description

The AirBnB clone project is a command-line and web-based application that simulates the core functionalities of the AirBnB platform. It includes features such as user management, property listings, and storage of data using a custom file-based storage engine.

## Features

- Command-line interface for managing objects (users, places, etc.).
- Object persistence using a custom file storage system.
- Modular codebase for scalability and maintainability.
- Unit tests to ensure code reliability.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/AirBnB_clone.git
   ```
2. Navigate to the project directory:
   ```bash
   cd AirBnB_clone
   ```
3. Ensure you have Python 3.x installed.

## Usage

### Command-Line Interface
Start the console:
```bash
./console.py
```
Available commands:
- `create <class_name>`: Creates a new object.
- `show <class_name> <id>`: Displays an object.
- `destroy <class_name> <id>`: Deletes an object.
- `all [<class_name>]`: Displays all objects.
- `update <class_name> <id> <attribute_name> <attribute_value>`: Updates an object.

### Web Interface
*Web interface functionality will be added in future versions.*

## Code Base Structure

```
/AirBnB_clone
├── console.py          # Entry point of the command-line interface
├── models/             # Contains all models
│   ├── base_model.py   # Base class for all models
│   ├── user.py         # User model
│   └── ...             # Other models
├── tests/              # Unit tests
│   ├── test_models/    # Tests for models
│   └── ...
└── README.md           # Project documentation
```

## License

This project is licensed under the MIT License.
