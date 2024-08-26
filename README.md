# Mall-Customer-Segmentation
**Mall Customer Segmentation** categorizes customers based on demographics and spending behavior using unsupervised machine learning (e.g., KMeans Clustering). By analyzing data such as age, gender, income, and spending scores, businesses identify distinct customer groups to tailor marketing strategies and improve engagement.

## Project Overview

The dataset includes customer information such as Customer ID, age, gender, annual income, and spending score. We apply the KMeans Clustering Algorithm using both scikit-learn and h2o to segment customers into meaningful groups.

## Contents

- **Data Exploration**: Analyzed the dataset using Pandas, including methods like `.info()`, `.describe()`, and `.isnull()`.
- **Data Visualization**: Created visualizations such as histograms, correlation matrices, and side-by-side bar charts using Matplotlib, Seaborn, and Plotly.
- **Model Training**: Implemented two clustering models:
  - **KMeans** using scikit-learn
  - **KMeans** using h2o for auto-training
- **Results**: Generated and analyzed cluster visualizations to understand customer segments.
- **Report**: Summarized findings and recommendations based on cluster analysis.

## Libraries Used

- `pandas`: For data manipulation and analysis.
- `matplotlib`, `seaborn`: For data visualization.
- `pickle`: For model serialization.
- `plotly`: For interactive visualizations.
- `scikit-learn`: For machine learning models and evaluation.
- `h2o`: For auto-training the clustering model.

## Getting Started

### Prerequisites

- Python 3.x
- Libraries: pandas, matplotlib, seaborn, plotly, scikit-learn, h2o

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/omar520/Mall-Customer-Segmentation.git
