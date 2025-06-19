# Remote Work and Mental Health

This project explores how remote work affects employee mental health and satisfaction. Using machine learning and clustering techniques, we analyze survey responses to uncover hidden patterns and segment employees by their experiences and stress levels.

## Project Structure

```
remote-work-mental-health/
├── data/
│   └── Impact_of_Remote_Work_on_Mental_Health.csv         # Public dataset from Kaggle
│
├── notebooks/
│   └── WQD7001_Project.ipynb                               # Full analysis and modeling notebook
│
├── model/
│   └── final_model.pkl                                     # Trained Random Forest model
│
├── results/                                                # Visualizations and evaluation outputs
│   ├── elbow_method.png                  # Elbow curve for optimal cluster selection
│   ├── feature_distribution.png          # Multiple pie/bar plots showing feature breakdown
│   ├── pca_clusters.png                  # PCA-reduced scatter plot with color-coded clusters
│   ├── sleep_quality_histogram.png       # Histogram for sleep quality distribution
│   ├── stress_level_barplot.png          # Bar plot showing stress level by category
│   ├── work_life_scatter.png             # Scatter plot comparing work-life balance factors
│
├── requirements.txt                                        # Python dependencies
├── README.md                                               # Project summary and reproducibility instructions

```

## Setup Instructions

1. Clone the repository or download the ZIP
2. Install dependencies:
```
pip install -r requirements.txt
```
3. Open the notebook:
```
jupyter notebook notebooks/WQD7001_Project.ipynb
```

## Data Privacy

This project uses synthetic, anonymized data available from:
👉 https://www.kaggle.com/datasets/waqi786/remote-work-and-mental-health

No personally identifiable information is used.

## Reproducibility Practices

- Fixed random seed for consistent results
- Clear documentation using markdown cells in notebooks
- All source code tracked with version control (Git)

## Authors

## Group Project Information

**Group Name:** Progression of a Group Project WQD7001, SEM 2 2024/2025 - OCC 1 - Group2

**Group Members:**

| No. | Name                        | Student ID |
|-----|-----------------------------|------------|
| 1   | Tioh Zi Cong                | 23078218   |
| 2   | YANG WENYIHAN               | 23094074   |
| 3   | Choo En Yi                  | 24084637   |
| 4   | Nurul Afzan Binti Nasir     | 24075178   |
| 5   | Toh Sin Tong                | 24071339   |

