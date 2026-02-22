# Setup

python -m venv .venv
source .venv/bin/activate || .venv\Scripts\activate
pip install --upgrade pip
pip install -r requirements.txt

# Test

pytest -q

# Lint

ruff check .

# Run

python main.py
