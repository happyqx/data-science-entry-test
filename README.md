# Pre-Assessment Notebooks (Q1 - Q7)

Assessment notebooks covering questions Q1 through Q7.

## Design Assumptions

The following assumptions and design considerations have been made when working on these notebooks:

- **Error Handling for Type Checking:** Unless otherwise explicitly stated to return -1 for type checking, an error will be raised instead when encountering invalid input types.
- **Numeric Definition:** In Python, the term "numeric" can exclude complex numbers in some contexts. However, for this assignment, complex numbers are included in the definition of numeric.
- **Code Implementation:** Solutions prioritize fulfilling task specifications as stated, without extensive refactoring.
- **Library Usage:** Libraries can be used in this assignment. Specifically, the `numbers` library has been utilized to support numeric type checking.
- **Folder Structure:** The folder organization is structured according to the submission instructions provided.

## Development Environment

This project was developed using:

- **Python version:** 3.13.12
- **IDE:** Visual Studio Code
- **Extensions:** Jupyter, Python

## Prerequisites

Before getting started, ensure you have the following installed:

- **Python 3.13.12** - Download from [python.org](https://www.python.org/downloads/)
  - Verify installation: `python --version`
  - Make sure to add Python to PATH during installation (Windows)

## Quick Setup

1. Create a virtual environment:

   ```bash
   python -m venv entry_test
   ```

2. Activate the virtual environment:

   ```bash
   # Windows:
   entry_test\Scripts\activate

   # macOS/Linux:
   source entry_test/bin/activate
   ```

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Open the project in VS Code and select the Python interpreter from your `entry_test` folder:
   - Press **Ctrl+Shift+P** to open the Command Palette
   - Type **"Python: Select Interpreter"** and press Enter
   - Choose the interpreter from `./entry_test/Scripts/python` (Windows) or `./entry_test/bin/python` (macOS/Linux)
   - Verify the status bar shows the selected venv interpreter

## Running Notebooks

- Press **Shift+Enter** to run a cell
- Click the **Play** button to run a cell
- All notebooks require the venv virtual environment to be active

## Files

- `Q1.ipynb` through `Q7.ipynb` - Assessment notebooks
- `requirements.txt` - Python dependencies
