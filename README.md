# Data-Driven Condition Assessment of Power Equipment

This project applies machine learning techniques to optimize the condition assessment of electrical power equipment, with a special focus on energy cables. By leveraging real-world diagnostic measurements, the project demonstrates how data-driven models can improve predictive maintenance, reduce unexpected failures, and enhance grid reliability.

### ⚠️ All data identifiers have been anonymized due to privacy policies. The datasets themselves are not included.

## Project Description
Modern power grid operators rely on a variety of diagnostic methods—including offline measurements (such as Tan Delta) and online monitoring (such as Partial Discharge)—to assess equipment condition. These techniques produce heterogeneous datasets in different formats, making analysis and integration challenging.

For this project, I received pre-collected diagnostic datasets in CSV format from an industrial partner. The datasets were already exported from a relational database where diverse diagnostic measurements had been integrated and modeled.

My role focused on applying machine learning techniques to analyze these datasets and support the condition assessment of energy cables. This involved:
- **Preparing and preprocessing the data for machine learning**
- **Applying clustering to explore underlying structures**
- **Detecting outliers and handling missing values**
- **Using supervised and semi-supervised learning to predict cable conditions**
- **Generating synthetic data to simulate future health trajectories**

## Machine Learning Applications

| Technique                 | Purpose                                                             |
| ------------------------- | ------------------------------------------------------------------- |
| Clustering                | Unbiased data grouping and visualization                            |
| Outlier Detection         | Identifying erroneous or abnormal measurements                      |
| Missing Value Imputation  | Handling incomplete diagnostic records                              |
| Supervised Learning       | Predicting equipment condition using labeled data                   |
| Semi-Supervised Learning  | Leveraging partially labeled datasets for improved generalization   |
| Synthetic Data Generation | Simulating future trajectories and exploring hypothetical scenarios |


## Project Structure

├── data-modelling-td.ipynb

├── supervised-learning-td.ipynb

├── semi-supervised-learning-td.ipynb

├── data-modelling-pd.ipynb

├── supervised-learning-pd.ipynb

└── semi-supervised-learning-pd.ipynb

## Notebooks Breakdown
* Tan Delta (TD)
data-modelling-td.ipynb: Clustering, outlier detection, and synthetic data generation

supervised-learning-td.ipynb: Classification models for TD-based diagnostics

semi-supervised-learning-td.ipynb: Semi-supervised learning with partial labels

* Partial Discharge (PD)
data-modelling-pd.ipynb: Clustering, outlier detection, and synthetic data generation

supervised-learning-pd.ipynb: Predictive models based on PD data

semi-supervised-learning-pd.ipynb: Enhancing performance with limited labeled data

## How to Run
* Clone the repository:
git clone https://github.com/MaryaSaki/project-repo.git
cd project-repo

* Install dependencies:
pip install -r requirements.txt

* Launch Jupyter Notebook:
jupyter notebook
Run notebooks in order, starting with data modelling.

## Built With
* Python

pandas

scikit-learn

seaborn / matplotlib

* Jupyter Notebook

## Contributing
Contributions are welcome! If you find a bug or have ideas to enhance the project, feel free to open an issue or submit a pull request.

## Contact
Created by Maryam Saki
Feel free to connect or reach out!

