# Data to Insight

Beginner-friendly materials for a short data analysis session in Python: slides, a lesson notebook and a practice notebook.
You will read a dataset, describe it, and answer simple questions with pandas and Matplotlib.

## What's inside

| Folder | Content |
|---|---|
| `slides/` | The presentation for the session |
| `lesson/` | Live-coding notebook on the 50 Startups dataset |
| `practice/` | Practice notebook on the Medical Costs dataset (a template with tasks and hints) |

## How to use

1. Go through the slides in `slides/`.
2. Follow the lesson notebook step by step and run each cell.
3. Open the practice notebook and solve it yourself.
4. Move on to the next step: a regression model (see below).

## Lesson

The lesson notebook covers three things:

- **Read the data:** `read_csv`, `shape`, `head`
- **Describe it:** `info`, missing values, `describe`, `value_counts`
- **Answer three simple questions:** scatter plots and correlation, and `groupby`

## Practice

The practice notebook repeats the same steps on a new dataset.
It is a template: each task is a short comment with a hint, and the code cells are empty.
Write your own code in them, then finish with a few sentences about what you found.

## Setup

```bash
pip install pandas matplotlib jupyter
jupyter notebook
```

You can also open the notebooks in [Google Colab](https://colab.research.google.com).

## Datasets

- Lesson: [50 Startups](https://raw.githubusercontent.com/dinesh19aug/ml-notes/master/Part-4-multiple-regression/50_Startups.csv)
- Practice: [Medical Cost Personal Dataset](https://www.kaggle.com/datasets/mirichoi0218/insurance)

## Next step

Build a regression model on the same 50 Startups data:
[linear-regression-from-scratch](https://github.com/zahrabakhshandeh/linear-regression-from-scratch)
