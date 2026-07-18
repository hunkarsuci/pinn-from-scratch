# PINNs from Scratch

A structured learning repository for physics-informed neural networks, Python, machine learning, and deep learning, with applications in mechanical engineering.

## Repository structure

```text
pinn-from-scratch/
├── lectures/
│   └── lecture_01/
│       └── lecture_01_python_scientific_computing.ipynb
├── src/
├── tests/
├── progress.md
├── requirements.txt
└── README.md
```

## VS Code setup

1. Open this repository folder in VS Code.
2. Install the Python and Jupyter extensions.
3. Create a virtual environment.
4. Install `requirements.txt`.
5. Open the Lecture 1 notebook and select the `.venv` kernel.

### Create the environment

Windows PowerShell:

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install --upgrade pip
pip install -r requirements.txt
```

macOS/Linux:

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
pip install -r requirements.txt
```
