# Installation Instructions

## 1. Create a Virtual Environment (.venv)

Open your terminal and run:

```fish
python3 -m venv .venv
```

This will create a new virtual environment named `.venv` in your project directory.

## 2. Activate the Virtual Environment

For the fish shell, activate with:

```fish
source .venv/bin/activate.fish
```

On powershell

```bash
.venv\Scripts\activate.ps1
```

## 3. Install Requirements

Once the virtual environment is activated, install the required packages:

```fish
pip install -r requirements.txt
```

You are now ready to start working on the project!
