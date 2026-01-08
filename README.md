# Anomaly Detection and Data Mining

This repository contains materials for the implementation and analysis of anomaly detection techniques. This project was developed as part of the Data Mining Algorithms (ADM) course at the Czech Technical University (CVUT) in Prague, during an academic exchange from the Universitat Politècnica de Catalunya (UPC).

The primary focus of this work is the identification of rare items, events, or observations which deviate significantly from the majority of the data. The repository includes practical applications such as fraud detection in financial transactions.

## Project Structure

The repository contains the following notebook:

* **ADM_Tutorial_02_Anomaly_Detection.ipynb**: The main Jupyter Notebook containing the theoretical background, implementation of detection algorithms, and visualization of outliers.

**Data Files**

* **data.npy**: A NumPy binary file containing general data used for initial distance-based and statistical anomaly detection exercises.
* **anomalyDATA.npy**: A specific dataset containing transactional features (value, time, agent's salary) and labels for fraud detection analysis.

## Getting Started

### Prerequisites

To run the analysis, you will need a Python environment with the following libraries installed:

```bash
pip install numpy pandas matplotlib scipy jupyter

```

### Usage

1. **Clone the repository:**
```bash
git clone https://github.com/JairoRY/CVUT-ADM-Anomaly-Detection.git
cd CVUT-ADM-Anomaly-Detection

```


2. **Launch the Jupyter Notebook:**
```bash
jupyter notebook ADM_Tutorial_02_Anomaly_Detection.ipynb

```



## Analysis Overview

The project covers several critical steps in the anomaly detection pipeline:

* **Data Exploration**: Visualization of data distributions to identify centers and global deviations.
* **Statistical Methods**: Using statistical measures and thresholds to isolate observations that do not conform to well-defined normal behavior.
* **Fraud Detection Analysis**: A specific case study using a 5-column transactional dataset to identify fraudulent activities based on transaction features and agent profiles.
* **Handling Uncertainty**: Managing datasets with incomplete labeling (NaN values) where the nature of a transaction (fraudulent or legitimate) is unknown.
