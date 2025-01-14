# MS Access to PostgreSQL Migration Script

This script allows you to migrate data from an MS Access database to a PostgreSQL database using pure Python.

## Prerequisites

Before running the script, ensure you have the following tools and libraries installed:

### System Packages

1. **mdbtools**: A suite of tools to read MS Access database files.
   - On **Ubuntu/Debian**:
     ```bash
     sudo apt-get install mdbtools
     ```
   - On **Fedora**:
     ```bash
     sudo dnf install mdbtools
     ```

2. **Python 3**: Ensure you have Python 3 installed on your system.

### Python Packages

1. **psycopg2**: A PostgreSQL adapter for Python.
   - Using `apt`:
     ```bash
     sudo apt install python3-psycopg2
     ```
   - Or, if you prefer using a virtual environment:
     ```bash
     sudo apt install python3-venv
     python3 -m venv myenv
     source myenv/bin/activate
     pip install psycopg2
     ```

## Usage

1. **Clone the repository or download the script** to your local machine.

2. **Navigate to the directory** containing the script:
   ```bash
   cd path/to/your/script

