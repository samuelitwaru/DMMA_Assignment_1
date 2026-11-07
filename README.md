---
noteId: "28684600dac911f1b0252f3adb171e7b"
tags: []

---

# DSC8307 Assignment 1 - Data Mining, Modeling and Analytics

Two independent, self-contained Jupyter notebooks for the Advent 2026 assignment.

## Contents

- `bank_marketing.ipynb` - Project 1: predicts term-deposit subscription from
  `data/bank-additional-full.csv`.
- `concrete_strength.ipynb` - Project 2: predicts concrete compressive strength from
  `data/Concrete_Data.csv`.
- `data/` - copies of the two provided CSVs so the notebooks run standalone.
- `requirements.txt` - pinned dependencies.

## How to run

```bash
python -m venv .venv
.venv\Scripts\activate        # Windows
pip install -r requirements.txt
jupyter notebook
```

Open either notebook and run all cells top to bottom (`Kernel > Restart & Run All`). Each
notebook reads its CSV with a path relative to the notebook's own directory (`data/...`), so run
Jupyter from this folder.
