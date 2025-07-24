# Task: Exploring and Visualizing the Iris Dataset

# Objective
The objective of this task is to explore and visualize the **Iris dataset** using Python libraries such as **pandas**, **seaborn**, and **matplotlib**. We aim to:
- Understand the structure of the dataset
- Summarize key characteristics
- Visualize feature relationships, distributions, and outliers

# Approach

1. Dataset Loading
   - Loaded the Iris dataset using `seaborn.load_dataset('iris')` into a pandas DataFrame.

2. Data Exploration
   - Used `.shape`, `.columns`, and `.head()` to understand the dataset structure.
   - Identified 4 numeric features and 1 categorical target (`species`).

3. Data Visualization
   - **Scatter Plots:** Used `sns.pairplot()` to observe pairwise relationships between numerical features for each species.
   - **Histograms:** Plotted histograms for each numerical column to analyze data distribution.
   - **Box Plots:** Plotted box plots to detect outliers and compare feature distributions across species.

# Results and Insights

- Scatter Plots: 
  Clear separation between species in feature space, especially for `petal_length` and `petal_width`, indicating they are strong discriminators.

- Histograms: 
  - `petal_length` and `petal_width` are clearly clustered into distinct ranges for different species.
  - `sepal_width` is more normally distributed but overlaps more across species.

- Box Plots:
  - Detected outliers mostly in `sepal_width`.
  - `setosa` species has significantly smaller petal features than others, confirming separability.

---

# Files
- `Data_Exploration_and_Visualisation_of_Iris_dataset.ipynb` – Python script notebook containing all code for loading, exploring, and visualizing the dataset.
- `README.md` – This summary file.

---

# Conclusion
This exploratory data analysis revealed clear feature differences among the three Iris species, especially in petal dimensions, which will be valuable for classification or predictive modeling tasks.
