# Task 1 - Iris Dataset EDA

DevelopersHub Corporation - Data Science & Analytics Internship

## What this task is about

This task was about getting comfortable with the basics of reading and visualizing a dataset in Python. I used the Iris dataset for this since it's small, clean, and commonly used for practicing EDA.

## What I did

I loaded the dataset using seaborn, then checked its shape, columns, and basic stats with pandas (`.shape`, `.columns`, `.head()`, `.describe()`). After confirming there were no missing values or duplicates, I moved on to visualizing it:

- A scatter plot of petal length vs petal width, colored by species
- Histograms for all four numeric features to see how they're distributed
- Box plots to check the spread and spot any outliers per species
- A correlation heatmap to see how the features relate to each other

## What I found

Petal length and petal width turned out to be the most useful features - just these two pretty much separate the three species on their own. Sepal measurements overlap a lot more between species, so they're less helpful for telling them apart. Setosa stood out as the most distinct species in basically every plot, while versicolor and virginica overlapped a bit, especially in petal length and sepal width. There were a couple of mild outliers in sepal width, mostly in virginica, but nothing major.

## Tools used

pandas, matplotlib, seaborn

## Files in this repo

- `Task1_Iris_EDA.ipynb` - the notebook with all the code, plots, and explanations
- `iris.csv` - the dataset used in this task

## Author

Nabeeha, BS Artificial Intelligence, Superior University Faisalabad
