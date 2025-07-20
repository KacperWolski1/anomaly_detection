# Anomaly Detection in Medicare Data

This project analyzes data from the Kaggle platform related to Medicare services, using machine learning methods for anomaly detection. Three algorithms are compared: **K-Means**, **Local Outlier Factor (LOF)**, and **Isolation Forest**.

## Source Data

The dataset is available on Kaggle:  
[Healthcare Providers Data For Anomaly Detection](https://www.kaggle.com/datasets/tamilsel/healthcare-providers-data/data)

## Project Goals

- Apply three unsupervised anomaly detection algorithms
- Evaluate and compare the effectiveness of each method
- Visualize the results and analyze outlier cases

## Methods Used

- **K-Means** – classifies points distant from centroids as anomalies
- **Local Outlier Factor (LOF)** – based on local density deviation
- **Isolation Forest** – uses random splits to isolate anomalies

## How to Run the Project Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/KacperWolski1/anomaly_detection.git
   cd anomaly_detection
2. Create an environment and install dependencies:
   pip install -r requirements.txt
3. Launch Jupyter Notebook:
   jupyter notebook
4. Open the notebook file and execute the cells step by step.

## Method Comparison

The notebook includes comparison tables and plots that illustrate the performance of each method.
