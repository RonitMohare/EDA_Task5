# EDA_Task5

# Titanic Dataset EDA - Task 5

This task is part of a data analysis assignment using the Titanic dataset. The objective was to perform exploratory data analysis (EDA) using `pandas`, `seaborn`, and `matplotlib`.



## 📌 Task Overview

We were instructed to:
- Use `.info()`, `.describe()`, and `.value_counts()` to explore the data
- Create pairplots and heatmaps for visual correlation analysis
- Use histograms, boxplots, and scatter plots to explore individual features
- Interpret and write observations for each plot

---

## 📊 What I Did

1. **Loaded the Dataset**
   - Used `train.csv` from the Titanic dataset.
   - Checked for null values, data types, and structure using `.info()`.

2. **Exploratory Data Analysis**
   - **`.describe()`**: Statistical summary of numerical columns.
   - **`.value_counts()`**: Frequency distribution for categorical features like `Sex`, `Pclass`, `Survived`.

3. **Visualizations**
   - 🔹 `sns.pairplot()`: Revealed survival trends by class and age.
   - 🔹 `sns.heatmap()`: Showed correlation—strong between `Fare` and `Pclass`.
   - 🔹 `plt.hist()`: Displayed age distribution.
   - 🔹 `sns.boxplot()`: Showed variation in age across passenger classes.
   - 🔹 `plt.scatter()`: Examined the relationship between age and fare.

---

## 📌 Observations

- **Survival Rate**: Higher among 1st class and younger passengers.
- **Age**: Most passengers were between 20–40 years.
- **Fare vs Age**: No strong relationship; fare depends more on class.
- **Heatmap**: `Fare` and `Pclass` are negatively correlated.
- **Boxplot**: 1st class passengers were generally older.

---

## 🛠 Tools & Libraries Used

- Python 3.x
- Jupyter Notebook
- pandas
- numpy
- seaborn
- matplotlib

---


