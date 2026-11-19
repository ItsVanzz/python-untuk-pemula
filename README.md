# Python for Beginners

A collection of code examples and study notes covering the basics of Python. All examples live in a single file, `main.py`, with comments in Indonesian at every step.

## Topics

`main.py` is organized in order, from the basics to an introduction to OOP:

1. Variables and data types: integer, float, string (single quote, double quote, multiline), boolean
2. Operators: arithmetic, comparison, and logical (`and`, `or`, `not`)
3. Conditionals: `if`, `elif`, `else`, and indentation rules
4. Loops: `for`, `while`, `break`, `continue`
5. Lists: indexing, negative indexing, `append`, `insert`, `remove`, `pop`, `clear`
6. Dictionaries: create, access, add, update, and delete items
7. Functions: parameters, `*args`, `**kwargs`, default values, return values
8. Classes and objects: constructor (`__init__`), methods, and the `self` parameter

## Project Structure

```
python-untuk-pemula/
├── main.py          # all code examples
├── screenshot/      # tutorial screenshots (tutorial-1.png to tutorial-8.png)
├── requirements.txt # dependency list (empty, standard library only)
├── .gitignore
└── README.md
```

## Requirements

- Python 3.10 or newer. The project was developed with Python 3.14.
- No extra packages. See `requirements.txt`.

## Getting Started

Clone the repository:

```bash
git clone https://github.com/ItsVanzz/python-untuk-pemula.git
cd python-untuk-pemula
```

Create and activate a virtual environment (optional, but recommended).

Bash or Zsh:

```bash
python -m venv venv
source venv/bin/activate
```

Fish:

```fish
python -m venv venv
source venv/bin/activate.fish
```

Windows (PowerShell):

```powershell
python -m venv venv
venv\Scripts\Activate.ps1
```

Install dependencies, then run:

```bash
pip install -r requirements.txt
python main.py
```

To leave the virtual environment, run `deactivate`.

## Notes

- Some lines in `main.py` are commented out on purpose because they raise errors (for example, writing `true` in lowercase or using wrong indentation). Remove the leading `#` to see the error message.
- The `venv/` and `__pycache__/` folders are not committed. Both are listed in `.gitignore`.

## Author

[ItsVanzz](https://github.com/ItsVanzz)
