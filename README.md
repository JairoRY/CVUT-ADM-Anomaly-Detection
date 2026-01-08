# Anomaly Detection

This repository contains materials for the implementation and analysis of anomaly detection techniques. This project was developed as part of the Data Mining Algorithms (ADM) course at the Czech Technical University (CVUT) in Prague, during an academic exchange from the Universitat Politècnica de Catalunya (UPC).

The primary focus is the identification of rare items or observations that deviate significantly from the majority of the data. The project includes practical applications such as fraud detection in financial transactions.

## Project Structure

The repository contains the following files:

* **ADM_Tutorial_02_Anomaly_Detection.ipynb**: The main Jupyter Notebook containing the theoretical background, implementation of detection algorithms, and visualization of outliers.

**Datasets**

* **data.npy**: A NumPy binary file containing a two-dimensional dataset used for initial distance-based and statistical anomaly detection exercises.
* **anomalyDATA.npy**: A transactional dataset comprising 5 columns (transaction value, time, agent's salary, and fraud labels) used for practical fraud detection analysis.

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



## Techniques Implemented

The project covers several critical methods used in the anomaly detection pipeline:

* **Statistical Thresholding**: Utilizing statistical distributions and centers to identify points that fall outside defined normal boundaries.
* **Mahalanobis Distance**: Implementing distance-based detection that accounts for the correlation between variables, allowing for more robust outlier identification in multivariate data.
* **Fraud Detection Analysis**: A specific case study involving transactional data where labels are used to evaluate the performance of detection thresholds.
* **Handling Unlabeled Data**: Managing "nan" values in labels where the nature of a transaction is unknown, simulating real-world financial monitoring challenges.
