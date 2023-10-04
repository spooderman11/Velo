# Velo
The ultimate and free MongoDB Data Migration Tool


## Features

- Export data from MongoDB collections to JSON files.
- Import data from JSON files into MongoDB collections.
- Create MongoDB collections if they don't exist during the import process.
- User-friendly command-line interface.
- Cross-platform compatibility (Windows and Unix-based systems).

## Prerequisites

Before using the Velo, please make sure you have the following requirements/prestiques installed:

- Python 3.9 or above
- pymongo library (install using `pip install pymongo`)
- rich library (install using `pip install rich`)

## Usage

1. Clone this repository to your local machine:
```bash
git clone https://github.com/spooderman11/Velo
```

2. Navigate to the directory of the project
3. Run the EXE inside the folder

### Exporting Data

- Choose option 1 to export data from MongoDB.
- Provide the connection string for your MongoDB server.
- Specify the database name.
- Optionally, enter the name of the collection you want to export (leave blank for all).
- The script will export data to JSON files in the project directory.

### Importing Data

- Choose option 2 to import data into MongoDB.
- Provide the connection string for your MongoDB server.
- Specify the database name.
- Ensure that the MongoDB database you want to import into already exists.
- The script will create collections (if they don't exist) and import data from JSON files.

## Acknowledgments

- [pymongo](https://pymongo.readthedocs.io/en/stable/index.html) - The Python driver for MongoDB.
- [rich](https://github.com/willmcgugan/rich) - A library for rich text and beautiful formatting in the terminal.

Enjoy using Velo for your MongoDB data management needs!
