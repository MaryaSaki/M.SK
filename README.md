# Data-Driven Condition Assessment of Power Equipment

This project applies machine learning techniques to optimize the condition assessment of electrical power equipment, with a special focus on energy cables. By leveraging real-world diagnostic measurements, the project demonstrates how data-driven models can improve predictive maintenance, reduce unexpected failures, and enhance grid reliability.

### ⚠️ All data identifiers have been anonymized due to privacy policies. The datasets themselves are not included.

## Project Description
Modern power grid operators rely on a variety of diagnostic methods—including offline measurements (such as Tan Delta) and online monitoring (such as Partial Discharge)—to assess the condition of power equipment. These diagnostic processes generate large volumes of heterogeneous data in different formats, making integration and analysis challenging.

For this project, I received pre-collected diagnostic datasets in CSV format from an industrial partner. These datasets were previously exported from a relational database that modeled and unified various offline and online measurements.

My role focused on applying machine learning techniques to analyze the datasets and support the condition assessment of energy cables. This involved:

- **Preparing and preprocessing the data for analysis**

- **Applying clustering and other unsupervised learning methods to explore natural groupings, patterns, and correlations**

- **Detecting outliers and identifying potentially erroneous measurements**

- **Investigating the effect of missing values by simulating missingness in key numeric and correlated features (e.g., with 0.1, 0.2, 0.4 missingness levels) and analyzing the impact on model accuracy**

- **Using supervised learning to predict equipment condition from fully labeled data**

- **Applying semi-supervised learning to leverage partially labeled datasets for improved generalization**

## Machine Learning Applications
| Technique                       | Purpose                                                                                         |
|--------------------------------|-------------------------------------------------------------------------------------------------|
| Clustering (Unsupervised Learning) | Discovering natural groupings, patterns, and correlations in unlabeled data                    |
| Outlier Detection               | Identifying erroneous or abnormal measurements                                                  |
| Missing Value Imputation        | Exploring impact of missing values by simulating data loss on key numeric/correlated features   |
| Supervised Learning             | Predicting equipment condition using labeled data                                               |
| Semi-Supervised Learning        | Leveraging partially labeled datasets for improved generalization                               |


## Project Structure

├── data-modelling-td.ipynb

├── supervised-learning-td.ipynb

├── semi-supervised-learning-td.ipynb

├── data-modelling-pd.ipynb

├── supervised-learning-pd.ipynb

└── semi-supervised-learning-pd.ipynb

## Notebooks Breakdown
#### Tan Delta (TD)
- **data-modelling-td.ipynb:** Clustering, correlation analysis, outlier detection, and missing value experiments

- **supervised-learning-td.ipynb:** Classification models for TD-based diagnostics

- **semi-supervised-learning-td.ipynb:** Semi-supervised learning using partial labels

#### Partial Discharge (PD)
- **data-modelling-pd.ipynb:** Clustering, correlation analysis, outlier detection, and missing value experiments

- **supervised-learning-pd.ipynb:** Supervised learning models based on PD measurements

- **semi-supervised-learning-pd.ipynb:** Enhancing model performance with limited labeled PD data

## How to Run
Clone the repository:
  
## How to Run

Clone the repository:
* git clone https://github.com/MaryaSaki/M.SK.git
cd M.SK

Install dependencies:
  
* pip install -r requirements.txt

Launch Jupyter Notebook:
  
* jupyter notebook

Run notebooks in order, starting with data modelling.

## Built With
Python

* pandas

* scikit-learn

* seaborn / matplotlib

Jupyter Notebook

## Contributing
Contributions are welcome! If you find a bug or have ideas to enhance the project, feel free to open an issue or submit a pull request.

## Contact
Created by Maryam Saki
Feel free to connect or reach out!

