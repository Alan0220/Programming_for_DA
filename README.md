 Programming for Data Analysis

This repository contains coursework, exercises, notebooks, and projects for **Programming for Data Analysis**.

## 📁 Project Structure

```text
Programming_for_DA/
├── data/          # Datasets and other data files
├── L1/            # Lesson 1 / coursework
│   └── L1.ipynb   # Jupyter Notebook for Lesson 1
├── .venv/         # Python virtual environment
├── pyproject.toml # Project configuration and dependencies
├── uv.lock        # Locked dependency versions
└── README.md      # Project documentation
```

## 🐍 Python Environment

This project uses **Python** with [`uv`](https://docs.astral.sh/uv/) for environment and dependency management.

The project includes the following main packages:

* **Pandas** — data manipulation and analysis
* **NumPy** — numerical computing
* **Matplotlib** — data visualization
* **Seaborn** — statistical data visualization
* **Jupyter** — interactive notebooks

## 🚀 Setup

Clone the repository:

```bash
git clone <repository-url>
cd Programming_for_DA
```

Create and activate the virtual environment:

```bash
uv venv
source .venv/bin/activate
```

Install the project dependencies:

```bash
uv sync
```

## 📓 Jupyter Notebook

To start Jupyter:

```bash
uv run jupyter lab
```

You can then open the notebooks located in the `L1/` directory.

For example:

```text
L1/L1.ipynb
```

## 📊 Main Libraries

Example imports used in the project:

```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
```

## 📦 Adding Dependencies

To add a new Python package:

```bash
uv add package-name
```

For example:

```bash
uv add pandas
uv add seaborn
uv add matplotlib
uv add jupyter
```

## 🗂️ Data

Datasets used for exercises and analysis should be stored in the `data/` directory.

```text
data/
├── dataset.csv
├── another_dataset.csv
└── ...
```

## 🎯 Goals

The project focuses on developing practical skills in:

* Python programming
* Data cleaning and manipulation
* Exploratory data analysis
* Data visualization
* Working with Pandas and NumPy
* Statistical analysis
* Jupyter Notebook workflows

## 📝 Notes

The project is developed as part of coursework and will be updated as new lessons and exercises are completed.

---

**Author:** Alan0220
**Course:** Programming for Data Analysis
