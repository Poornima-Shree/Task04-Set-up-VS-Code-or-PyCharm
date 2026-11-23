# Iris Dataset Analysis – Data Science Level 1 Internship

## Project Overview
This project focuses on exploring and analyzing the Iris dataset using Python. The goal is to understand the dataset, perform basic data cleaning, calculate statistics, and create visualizations to identify patterns and relationships between flower measurements.

## Dataset
- **Dataset Name:** Iris Dataset
- **Source:** [UCI Machine Learning Repository – Iris Dataset](https://archive.ics.uci.edu/dataset/53/iris)
- **Total Records:** 150
- **Total Features:** 4 numerical features
- **Target Column:** Species
- **Number of Species:** 3 (Setosa, Versicolor, Virginica)

### Features
1. Sepal Length
2. Sepal Width
3. Petal Length
4. Petal Width

## Technologies Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Project Tasks

1. Imported the required Python libraries.
2. Loaded the Iris dataset into a Pandas DataFrame.
3. Explored the dataset using `head()`, `info()`, `shape`, and `describe()`.
4. Checked for missing values and duplicate records.
5. Analyzed the distribution of Iris species.
6. Calculated average measurements for each species.
7. Created visualizations to understand the data.
8. Used boxplots to compare petal lengths across species.
9. Created scatter plots to examine relationships between petal length and petal width.
10. Created a correlation heatmap to understand relationships between numerical features.

## Visualizations
The project includes:
- Species count plot
- Correlation heatmap
- Petal length boxplot
- Petal length vs. petal width scatter plot

## Key Findings

- The dataset contains 150 flower records belonging to three Iris species.
- Each species has 50 records.
- Setosa generally has smaller petal measurements than the other two species.
- Virginica generally has the largest petal measurements.
- Petal length and petal width have a strong positive relationship.
- The visualizations show that petal measurements help distinguish the three species.

## Project Structure

```text
DataScience_Internship/
└── Level_1_Iris_Dataset_Analysis/
    ├── Iris_Dataset_Analysis.ipynb
    ├── README.md
    └── requirements.txt
```

## How to Run the Project

1. Clone or download this repository.
2. Open the project folder in VS Code.
3. Make sure Python and Jupyter are installed.
4. Install the required libraries:

```bash
pip install -r requirements.txt
```

5. Open `Iris_Dataset_Analysis.ipynb` in VS Code.
6. Run the notebook cells one by one to view the analysis and visualizations.

## Conclusion

This project provided practical experience in data analysis using Python. It helped develop an understanding of data loading, data exploration, basic data cleaning, statistical analysis, and data visualization.

The analysis shows that petal measurements are useful for distinguishing different Iris species.

## Internship Project
**Level:** Data Science – Level 1  
**Project:** Iris Dataset Analysis  
**Tools:** Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook
