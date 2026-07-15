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

## First GitHub publication

```bash
git init
git add .
git commit -m "chore: initialize PINN learning repository"
git branch -M main
git remote add origin YOUR_GITHUB_REPOSITORY_URL
git push -u origin main
```

## Regular study-session update

```bash
git status
git add .
git commit -m "lecture 01: complete NumPy and residual exercises"
git push
```

Use focused commit messages, for example:

- `lecture 01: complete Python foundations`
- `lecture 01: add derivative convergence experiment`
- `docs: update learning progress`
- `fix: correct residual calculation`
- `refactor: move numerical utilities into src`
