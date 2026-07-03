# Week 5 - Professional Project Structure & Relative Paths

## Project Description

This project demonstrates how to organize a Python data analysis project using a professional folder structure and relative file paths. The dataset is loaded with pandas, making the project portable so it can run on any computer without changing file locations.

## Project Structure

```
project_folder/
├── _data/
│   └── insurance (4).csv
├── notebook.ipynb
└── README.md
```

## Data

The dataset is stored in the `_data` folder.

**Source:** Insurance dataset downloaded from a government website.

The dataset contains the following columns:

| Column       | Description |
|--------------|--------------------------------------------------------------------|
| age          | Age of the person (18–64 years) |
| sex          | Male or Female |
| bmi          | Body Mass Index (BMI), a measure of body weight relative to height |
| children     | Number of children covered by insurance (0–5) |
| smoker       | Whether the person is a smoker (Yes/No) |
| region       | Residential region (northeast, northwest, southeast, southwest) |
| charges      | Individual medical insurance charges |

## How to Run

1. Install Python.
2. Install pandas if it is not already installed.

```bash
pip install pandas
```

3. Open `notebook.ipynb` in Jupyter Notebook.
4. Run all notebook cells using the Python kernel.

The dataset is loaded using the following relative path:

```python
import pandas as pd

df = pd.read_csv("_data/insurance (4).csv")
```

## Why Use Relative Paths?

Relative paths make the project portable because they do not depend on a specific computer.

- **Absolute paths** only work on the original computer where the file is stored.
- **Relative paths** allow anyone to run the project as long as they keep the same project structure.

## What I Learned

- How to organize a project using a clear folder structure.
- How to load datasets using relative paths instead of absolute paths.
- How to write a professional README using Markdown.
- Why project organization improves readability and collaboration.
