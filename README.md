
# Iris Dataset – Exploratory Data Analysis

An exploratory data analysis project using the Iris Flower Dataset to study and visualize the differences between three flower species: Setosa, Versicolor, and Virginica.

The project uses Python and data visualization libraries to explore flower measurements, identify patterns, examine feature relationships, and understand the distribution of each species.

## Project Overview

The analysis focuses on four numerical features:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

The dataset is downloaded using KaggleHub, cleaned using Pandas, and explored through statistical analysis and visualizations.

## Key Features

- Automatic dataset download using KaggleHub.
- Duplicate record identification and removal.
- Species name cleaning and standardization.
- Statistical summary of numerical features.
- Species-wise feature distribution analysis.
- Pair plots for comparing multiple features.
- Box plots for examining feature distributions.
- Correlation heatmap for identifying relationships between features.
- Export of the cleaned dataset as a CSV file.

## Dataset

The project uses the Iris Flower Dataset, which contains measurements from three flower species.

| Species | Description |
|---|---|
| Setosa | First Iris species |
| Versicolor | Second Iris species |
| Virginica | Third Iris species |

The dataset includes four measurements for each flower:

| Feature | Description |
|---|---|
| Sepal Length | Length of the sepal |
| Sepal Width | Width of the sepal |
| Petal Length | Length of the petal |
| Petal Width | Width of the petal |

## Data Analysis and Visualizations

### 1. Statistical Analysis

- Dataset overview and structure.
- Species distribution and frequency counts.
- Mean and standard deviation.
- Minimum and maximum values.
- Percentile-based analysis.
- Species-wise statistical summaries.

### 2. Pair Plot

Compares all numerical features against one another and uses species categories to highlight differences in their measurements.

### 3. Box Plots

Displays the distribution of each feature, including median values, quartiles, and potential outliers.

### 4. Correlation Heatmap

Shows the correlation between sepal and petal measurements to identify positive and negative relationships among features.

## Technologies Used

| Technology | Purpose |
|---|---|
| Python 3 | Programming language |
| Pandas | Data cleaning and analysis |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualizations |
| KaggleHub | Dataset downloading |
| Jupyter Notebook | Analysis environment |
| Google Colab | Cloud-based notebook execution |

## Project Structure

```text
iris_project/
│
├── analysis.ipynb
├── iris_clean.csv
├── pairplot.png
└── boxplots_correlation.png
```

| File | Description |
|---|---|
| `analysis.ipynb` | Complete data analysis and visualization pipeline |
| `iris_clean.csv` | Cleaned dataset exported after preprocessing |
| `pairplot.png` | Pairwise feature comparison |
| `boxplots_correlation.png` | Feature box plots and correlation heatmap |

## Getting Started

### 1. Clone the Repository

```bash
git clone YOUR_REPOSITORY_URL
```

### 2. Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn kagglehub
```

### 3. Open the Notebook

Open `analysis.ipynb` using Jupyter Notebook or Google Colab.

### 4. Run the Analysis

Execute the notebook cells in order to:

1. Download the dataset.
2. Clean and preprocess the data.
3. Perform statistical analysis.
4. Generate visualizations.
5. Export the cleaned dataset and plots.

## Learning Outcomes

This project provides practical experience in:

- Data collection and preprocessing.
- Handling duplicate records.
- Exploratory Data Analysis (EDA).
- Descriptive statistics.
- Data visualization.
- Feature correlation analysis.
- Working with Python data science libraries.

## Author

**Muhammad Sameer Mustaqeem**

- GitHub: [sameermustaqeem878-source](https://github.com/sameermustaqeem878-source)
- LinkedIn: [Muhammad Sameer Mustaqeem](https://www.linkedin.com/in/m-sameer-mustaqeem-b1a436317/)
