# Math Tutor — Jupyter Notebooks

Short collection of Jupyter notebooks used for linear algebra and coordinate geometry tutorials (plotting lines/planes, determinants, inverses, vector operations).

## Contents
- `set1.ipynb` — Coordinate geometry: plotting lines and planes, vector ops.
- `set2.ipynb` — Matrix arithmetic, determinants, cofactors and inverses.
- `set3.ipynb` — Determinant properties and examples.
- `.gitignore` — recommended ignore rules.

## Recommended Python environment
- Python 3.10 or 3.11 (better wheel availability)
- Create a venv and install requirements (see below)

## Minimal setup (Windows PowerShell)
```powershell
python -m venv .venv
.\.venv\Scripts\activate
python -m pip install -U pip setuptools wheel
python -m pip install -r requirements.txt
jupyter notebook
```

## Suggested requirements
- numpy
- matplotlib 
- notebook # to use jupyter
- nbconvert # to convert to html
- ipympl #
- ipywidgets # generate interactive plots

(You can remove `ipympl`/`ipywidgets` if you prefer static plots only.)
