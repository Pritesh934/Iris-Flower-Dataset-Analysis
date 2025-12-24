# 🌸 Iris Dataset Exploratory Data Analysis (EDA)

This project performs a comprehensive Exploratory Data Analysis (EDA) on the classic Iris flower dataset. The goal is to understand the underlying structure of the data, visualize relationships between features, and prepare the data for potential machine learning modeling.

## 📂 Project Overview

The analysis follows a structured approach to uncover patterns in the data, including:
1.  **Data Inspection**: Understanding the shape, data types, and summary statistics.
2.  **Data Cleaning**: Checking for missing values, duplicates, and data imbalance.
3.  **Visualization**: Using 2D and 3D plots to visualize feature distributions and class separability.
4.  **Correlation Analysis**: Identifying relationships between numerical features.
5.  **Outlier Detection**: Using statistical methods to identify and handle outliers.

## 📊 Dataset

The dataset used is the **Iris Dataset**, which contains measurements for 150 iris flowers from three different species:
* **Iris-setosa**
* **Iris-versicolor**
* **Iris-virginica**

**Features:**
* `SepalLengthCm`: Length of the sepal (in cm)
* `SepalWidthCm`: Width of the sepal (in cm)
* `PetalLengthCm`: Length of the petal (in cm)
* `PetalWidthCm`: Width of the petal (in cm)

## 🛠️ Technologies & Libraries Used

The project is implemented in Python using a Jupyter Notebook. Key libraries include:

* **Pandas**: For data manipulation and analysis.
* **NumPy**: For numerical operations.
* **Matplotlib & Seaborn**: For static data visualization (histograms, scatter plots, box plots, heatmaps).
* **Plotly Express**: For interactive 3D visualizations.
* **Scikit-learn**: For datasets and preprocessing tasks.

## 📈 Key Visualizations

The notebook includes several insightful visualizations:
* **Scatter Plots**: To observe the relationship between Sepal and Petal dimensions.
* **Pair Plots**: To compare all variables against each other pairwise.
* **Histograms & Distribution Plots**: To view the frequency distribution of features.
* **Box & Violin Plots**: To analyze the spread of data and detect outliers.
* **Heatmap**: To visualize the correlation matrix between features.
* **3D Scatter Plot**: An interactive plot showing three dimensions of data simultaneously.

## 🚀 How to Run

1.  Clone this repository.
2.  Ensure you have the required libraries installed:
    ```bash
    pip install pandas numpy matplotlib seaborn plotly scikit-learn
    ```
3.  Open the Jupyter Notebook:
    ```bash
    jupyter notebook Iris_EDA.ipynb
    ```
4.  Run the cells sequentially to reproduce the analysis.

> **Note**: Ensure the dataset file `Iris Dataset.csv` is in the same directory as the notebook. If your file is named differently (e.g., `Iris.csv`), update the `pd.read_csv()` line in the code.
