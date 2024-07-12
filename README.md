# ds-eda-project

EDA project by Christian R.

## Requirements

This repository requires the installation of the following tools:

- nodeJS
- pyenv (+python 3.11.3)

## Setup

Check if node is installed by running

```sh
node -v
```

Create a virtual environment and install dependencies 

For `Linux` and `MacOS`:

```bash
pyenv local 3.11.3
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```

For `PowerShell`:

```PowerShell
pyenv local 3.11.3
python -m venv .venv
.venv\Scripts\Activate.ps1
pip install --upgrade pip
pip install -r requirements.txt
```

For `Git-Bash`:
```
pyenv local 3.11.3
python -m venv .venv
source .venv/Scripts/activate
pip install --upgrade pip
pip install -r requirements.txt
```


