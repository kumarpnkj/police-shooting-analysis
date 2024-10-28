# Police Shooting Analysis (2016-2024)

This project explores patterns of police shootings across the continental United States from 2016 to 2024 using clustering analysis. The analysis was performed using k-means clustering to identify regional differences in the characteristics of these incidents.

## Overview

The goal of this project is to use clustering to better understand the spatial and demographic characteristics of police shootings in the United States. We used data from publicly available sources to identify regions that experienced the most incidents, assess racial and demographic patterns, and provide insights that could help policymakers and law enforcement agencies plan targeted interventions.

## Data

The dataset used for this analysis includes the following key variables:
- **Latitude and Longitude**: Used to geographically map each incident.
- **Armed Status**: Whether the individual was armed and, if so, the type of weapon.
- **Demographic Variables**: Information on age, race, and gender.
- **Cluster Assignment**: The incidents were grouped into three clusters to highlight similarities and differences across regions.

## Analysis

- **Clustering Method**: k-means clustering was applied to identify groups of incidents with similar characteristics. The Elbow Method and Silhouette Scores were used to determine the optimal number of clusters.
- **Geodesic Distance Calculation**: The geodesic distance from the centroid of each cluster was computed to analyze the spatial distribution of incidents within each cluster.
- **Data Visualization**: Various plots were generated, including geographic distributions, incident counts, demographic breakdowns, and armed status categories.

## Figures

- **Figure 1**: The Elbow Method for Determining Optimal Number of Clusters (`k=3`).
- **Figure 2**: Silhouette Scores for Different Values of `k`.
- **Figure 3**: Number of Incidents per Cluster.
- **Figure 4**: Geographic Distribution of Police Shooting Clusters.
- **Figure 5**: Age Distribution by Cluster.
- **Figure 6**: Number of Incidents by Race for Each Cluster.
- **Figure 7**: Monthly Distribution of Incidents.
- **Figure 8**: Number of Incidents by Armed Status for Each Cluster.
- **Figure 9**: Geodesic Distance Distribution per Cluster.

## Jupyter Notebook

The complete analysis, including the code and visualizations, is available in the Jupyter notebook. You can view and run the notebook via GitHub:

[Police Shooting Analysis Notebook](https://github.com/kumarpnkj/police-shooting-analysis/blob/main/police-shooting-analysis.ipynb)

## How to Run the Analysis

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/kumarpnkj/police-shooting-analysis.git
   ```
2. Navigate to the directory:
   ```bash
   cd police-shooting-analysis
   ```
3. Open the Jupyter notebook:
   ```bash
   jupyter notebook police-shooting-analysis.ipynb
   ```
4. Follow the instructions within the notebook to run the analysis.

## Requirements

- Python 3.x
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Geopy
- Scikit-Learn

Install the required packages using:
```bash
pip install pandas numpy matplotlib seaborn geopy scikit-learn
```

## License

This project is licensed under the MIT License. Feel free to use and modify the code for your own purposes.
