# MET CS555

Course work for MET CS555 (Data Analysis and Visualization) — Chris Davis.

## Layout

| Folder | Status |
|--------|--------|
| `module-1/` | Homework 1 — hospital stay durations |
| `module-2/` | Homework 2 — meal prep and calorie intake |
| `module-3/` | Homework 3 — fish meals and mercury levels |
| `module-4/` | Homework 4 — occupational prestige regression |
| `module-5/` | Placeholder |
| `module-6/` | Placeholder |
| `term-project/` | Placeholder |

Each completed module usually includes:

- Jupyter notebook (`.ipynb`) with answers and appendix code
- HTML export for submission
- Data CSV and any generated plots

## Running notebooks

From a module folder:

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install numpy pandas matplotlib scipy jupyter
jupyter notebook
```

Export HTML:

```bash
jupyter nbconvert --to html --output DAVIS_Homework_N.html DAVIS_Homework_N.ipynb
```
