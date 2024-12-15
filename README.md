# Causal trees demo

## Prerequisites

- Python 3.9 (may work with other versions but I tested it with 3.9.)

  **If Python 3.9 is not installed:**
    - **MacOS:**
    1. Install Homebrew (if not already installed):
       ```bash
       /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
       ```
    2. Use Homebrew to install Python 3.9:
       ```bash
       brew install python@3.9
       ```
    3. Ensure Python 3.9 is in your PATH:
       ```bash
       echo 'export PATH="/usr/local/opt/python@3.9/bin:$PATH"' >> ~/.zshrc
       source ~/.zshrc
       ```
    4. Verify installation:
       ```bash
       python3.9 --version
       ```
  - **Linux:**
    ```bash
    sudo apt update
    sudo apt install python3.9
    sudo apt install python3.9-venv
    ```
  - **Windows:**
    1. Download the Python 3.9 installer from [python.org](https://www.python.org/downloads/release/python-390/).
    2. Run the installer and make sure to check the option to "Add Python to PATH" during installation.

## Setup instructions

### 1. Clone the repository

In terminal, navigate to where you'd like to store the repository and run:
```bash
git clone https://github.com/4Freye/causal_trees_demo.git
cd causal_trees_demo
```

### 2. Create a virtual environment

Create a Python virtual environment to isolate the project dependencies:

```bash
python3.9 -m venv .venv
source .venv/bin/activate  # Linux/MacOS
.\.venv\Scripts\activate   # Windows
```

### 3. Install dependencies

Install the necessary Python packages using `pip`:

```bash
pip install -r requirements.txt
```

### 4. Open the demo notebook

1. Open the `demo.ipynb` notebook in the repository.
2. Ensure that `.venv` is selected as the Python environment:
   - In Visual Studio Code, open the Command Palette (`Ctrl+Shift+P` or `Cmd+Shift+P` on Mac).
   - Search for and select **Python: Select Interpreter**.
   - Choose the interpreter located in `.venv`.

**Tip:**

- If `.venv` does not appear as an option, you may need to close the Visual Studio Code window and reopen it after installing the virtual environment.