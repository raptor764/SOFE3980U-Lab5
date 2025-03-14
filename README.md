# Data Quality Lab for Software Quality Course

## Repository Structure

```
/ (root)
│── data/
│   ├── Labels.csv  # Dataset for analysis
│
│── notebooks/
│   ├── 1_great_expectations.ipynb  # Data validation with Great Expectations
│   ├── 2_cleanlab.ipynb  # Detecting label errors with Cleanlab
│
│── requirements.txt  # Python dependencies
│── README.md  # Lab instructions
```

## `requirements.txt`
```
great-expectations
pandas
numpy
matplotlib
seaborn
cleanlab
scikit-learn
jupyter
```

## `README.md`
```md
# Data Quality Lab

This lab teaches students how to assess and improve data quality using:
1. **Great Expectations** for data validation.
2. **Cleanlab** for identifying label errors.

## Setup
1. Clone the repository:
   ```sh
   git clone <repo_link>
   cd data_quality_lab
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Open Jupyter Notebook:
   ```sh
   jupyter notebook
   ```

## Part 1 - Data Validation (Great Expectations)
- Open `notebooks/1_great_expectations.ipynb` and follow the steps.

## Part 2 - Label Issues Detection (Cleanlab)
- Open `notebooks/2_cleanlab.ipynb` to detect label errors in the dataset.
