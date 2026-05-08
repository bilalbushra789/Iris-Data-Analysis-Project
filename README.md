# DevelopersHub Corporation — Data Science & Analytics Internship Tasks



**Program:** Data Science & Analytics Internship


## Task 1: Exploring and Visualizing the Iris Dataset

###  Objective
Understand how to read, summarize, and visualize a dataset using Python. The goal is to apply core data science skills including data loading, inspec
tion, and multiple visualization techniques.

###  Dataset
- **Name:** Iris Dataset
- **Source:** Downloded online (CSV) 
- **Size:** 150 rows × 5 columns
- **Classes:** 3 species — *Setosa*, *Versicolor*, *Virginica*
- **Features:** sepal_length, sepal_width, petal_length, petal_width

###  Approach
1. Loaded dataset using `seaborn.load_dataset()` (fetches directly from GitHub URL)
2. Inspected structure with `.shape`, `.columns`, `.head()`, `.info()`, `.describe()`
3. Checked for missing values — dataset was clean
4. Created multiple visualizations:
   - **Scatter Plots** — to analyze relationships between sepal/petal dimensions
   - **Pair Plot** — to see all feature combinations at once
   - **Histograms** — to examine distribution of each feature per species
   - **KDE Plots** — for smooth density comparison across species
   - **Box Plots** — to detect outliers and measure spread
   - **Violin Plots** — combining distribution + box plot insight
   - **Correlation Heatmap** — to find feature relationships

###  Results & Key Insights
| Insight | Finding |
|---|---|
| Best separating features | **Petal length & petal width** |
| Most distinct species | **Iris Setosa** — smallest petals, clearly separable |
| Highest correlation | Petal length ↔ Petal width = **0.96** |
| Missing values | **None** — clean dataset |
| Outliers | Very few, mostly in sepal width of Setosa |

###  Libraries Used
```python
pandas    # Data loading and manipulation
numpy     # Numerical operations
matplotlib # Static plotting
seaborn   # Statistical visualizations
```

### How to Run
```bash
# Option 1 — Jupyter Notebook
jupyter notebook Task1_Iris_Exploration.ipynb

# Option 2 — JupyterLab
jupyter lab Task1_Iris_Exploration.ipynb
```


---
