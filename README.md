# Python Snippets and Notebooks

A curated collection of Jupyter notebooks and notes covering Python fundamentals: basics, control flow, built-in data structures, functions, modules/packages, file handling, and exceptions.

## Structure

- `1-Python_Bascis/`: Python basics, variables, data types, and operators
- `2-Control_Flow/`: Conditionals and loops
- `3-Inbuilt_data_structures_in_python/`: Lists, tuples, sets, dictionaries, and examples
- `4_functions/`: Functions, lambda, `map`, `filter`
- `5_modules_and_packages/`: Imports and standard library examples
- `6_file_handling/`: File operations and paths
- `7_exception_handling/` (planned): Exception handling

Each folder contains `.ipynb` notebooks and matching `*_notes.md` files where applicable.

## Getting Started

### Prerequisites

- Python 3.9+ recommended
- `pip` for package management

### Setup

```bash
# Clone the repository
git clone https://github.com/your-username/python-snippet.git
cd python-snippet

# Create and activate a virtual environment (optional but recommended)
python -m venv .venv
# Windows PowerShell
.\.venv\Scripts\Activate.ps1
# or Windows cmd
.\.venv\Scripts\activate.bat
# or bash
source .venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Start Jupyter
python -m ipykernel install --user --name python-snippet
jupyter notebook
```

## Requirements

See `requirements.txt`. Current minimal set:

- `ipykernel`
- `numpy`

Add more as notebooks require them (e.g., `pandas`, `matplotlib`).

## Usage

- Open the desired `.ipynb` under the relevant topic folder.
- Run cells sequentially; refer to accompanying `*_notes.md` for explanations.

## Contributing

- Keep notebooks focused and self-contained.
- Prefer small, topic-scoped additions.
- Do not commit large data files; add new dependencies to `requirements.txt`.

## License

Specify a license here if applicable (e.g., MIT).
