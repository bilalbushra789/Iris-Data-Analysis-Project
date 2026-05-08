# 📊 DevelopersHub Corporation — Data Science & Analytics Internship Tasks

**Intern:** [Your Name Here]
**Due Date:** 15th May, 2026
**Program:** Data Science & Analytics Internship

---

## 📁 Repository Structure

```
📦 developershub-ds-internship
 ┣ 📓 Task1_Iris_Exploration.ipynb       ← Task 1: Iris Dataset EDA & Visualization
 ┣ 📓 Task2_Credit_Risk_Prediction.ipynb ← Task 2 (coming soon)
 ┣ 📓 Task3_Customer_Churn.ipynb         ← Task 3 (coming soon)
 ┣ 📓 Task4_Insurance_Claims.ipynb       ← Task 4 (coming soon)
 ┣ 📓 Task5_Loan_Acceptance.ipynb        ← Task 5 (coming soon)
 ┗ 📄 README.md
```

---

## ✅ Task 1: Exploring and Visualizing the Iris Dataset

### 🎯 Objective
Understand how to read, summarize, and visualize a dataset using Python. The goal is to apply core data science skills including data loading, inspection, and multiple visualization techniques.

### 📂 Dataset
- **Name:** Iris Dataset
- **Source:** Loaded directly via `seaborn` — **no manual download required**
- **URL:** `https://raw.githubusercontent.com/mwaskom/seaborn-data/master/iris.csv`
- **Size:** 150 rows × 5 columns
- **Classes:** 3 species — *Setosa*, *Versicolor*, *Virginica*
- **Features:** sepal_length, sepal_width, petal_length, petal_width

### 🛠️ Approach
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

### 📊 Results & Key Insights
| Insight | Finding |
|---|---|
| Best separating features | **Petal length & petal width** |
| Most distinct species | **Iris Setosa** — smallest petals, clearly separable |
| Highest correlation | Petal length ↔ Petal width = **0.96** |
| Missing values | **None** — clean dataset |
| Outliers | Very few, mostly in sepal width of Setosa |

### 🧰 Libraries Used
```python
pandas    # Data loading and manipulation
numpy     # Numerical operations
matplotlib # Static plotting
seaborn   # Statistical visualizations
```

### ▶️ How to Run
```bash
# Option 1 — Jupyter Notebook
jupyter notebook Task1_Iris_Exploration.ipynb

# Option 2 — JupyterLab
jupyter lab Task1_Iris_Exploration.ipynb
```
> ⚠️ No dataset download needed. Just run the notebook — it fetches data automatically!

---

## 🚀 Git Push Steps (Step-by-Step)

### First Time Setup

```bash
# Step 1: Create a new folder for your project and go into it
mkdir developershub-ds-internship
cd developershub-ds-internship

# Step 2: Initialize a git repository
git init

# Step 3: Set your GitHub username and email (only needed once)
git config --global user.name "Your Name"
git config --global user.email "your@email.com"
```

### Add Your Files

```bash
# Step 4: Copy your notebook and README into this folder, then add all files
git add .

# Step 5: Commit with a descriptive message
git commit -m "Add Task 1 - Iris Dataset Exploration and Visualization"
```

### Push to GitHub

```bash
# Step 6: Go to github.com → click "New Repository"
#          Name it: developershub-ds-internship
#          Keep it Public, do NOT initialize with README (you already have one)

# Step 7: Link your local repo to GitHub (replace YOUR_USERNAME with your GitHub username)
git remote add origin https://github.com/YOUR_USERNAME/developershub-ds-internship.git

# Step 8: Push your code to GitHub
git branch -M main
git push -u origin main
```

### For Future Tasks (Task 2, 3, 4, 5)

```bash
# After adding a new notebook, just run:
git add Task2_Credit_Risk_Prediction.ipynb
git commit -m "Add Task 2 - Credit Risk Prediction"
git push
```

---

## 📌 Submission
Submit your GitHub repository link on **Google Classroom**.

---

*DevelopersHub Corporation — Data Science & Analytics Internship 2026*
