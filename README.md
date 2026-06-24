# Task 1: Exploring and Visualizing the Iris Dataset

**Internship:** DevelopersHub Corporation — Data Science & Analytics Internship Program

## 📌 Task Objective
Understand how to read, summarize, and visualize a dataset using Python. This task uses the
classic **Iris dataset** to practice data loading, inspection, and exploratory visualization.

## 🛠️ Approach
1. Loaded the Iris dataset using `seaborn.load_dataset()` (150 samples, 3 species).
2. Inspected the dataset's structure using `.shape`, `.columns`, `.head()`, `.info()`, and `.describe()`.
3. Verified data quality — checked for missing values and duplicate rows.
4. Created visualizations using **matplotlib** and **seaborn**:
   - Scatter plot (petal length vs petal width, colored by species)
   - Histograms (distribution of all 4 numeric features)
   - Box plots (spread and outlier detection per species)
   - Correlation heatmap (bonus)

## 📊 Results & Insights
- The dataset is clean with no missing values or duplicates, and perfectly balanced (50 samples/species).
- **Petal length and petal width** are the most discriminative features — they almost perfectly separate
  the three species on their own.
- **Sepal measurements overlap more** across species, making them less reliable for classification.
- *Setosa* is consistently the most distinct/separable species across every plot.
- A few mild outliers were detected in `sepal_width`, mainly for *virginica*.

## 🧰 Tools & Libraries
`pandas` · `matplotlib` · `seaborn`

## 📁 Files
- `Task1_Iris_EDA.ipynb` — Full Jupyter notebook with code, visualizations, and written insights.

## 👤 Author
Nabeeha — BS Artificial Intelligence, Superior University Faisalabad
