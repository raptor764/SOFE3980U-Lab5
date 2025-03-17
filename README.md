# Data Quality

This lab guides students through assessing and improving data quality using:
1. **Great Expectations** for data validation.
2. **Cleanlab** for identifying label errors.

## Repository:   
[https://github.com/zubxxr/SOFE3980U-Lab5](https://github.com/zubxxr/SOFE3980U-Lab5) 

## 1. Great Expectations

Great Expectations (GX) is an open-source data validation framework that helps ensure data quality by defining, testing, and documenting expectations for datasets. It provides tools for profiling data, creating validation rules, and generating reports to maintain data integrity in pipelines.

To start working with it, navigate to the [Great Expectations Notebook](https://github.com/zubxxr/SOFE3980U-Lab5/blob/main/Great_Expectations.ipynb) and download it. This is a Google Colab Notebook, an interactive environment that allows you to write and execute Python code in the cloud without needing to set up anything on your local machine. 

After downloading it, go into Google Drive, and import the notebook into there. Then double click on the file to open it.

Go through the notebook and follow the steps to install the necessary libraries, load the dataset, and set up data validation with Great Expectations. The notebook demonstrates the process of loading the UCI Adult dataset, defining data expectations, and validating those expectations against the dataset. The goal is to ensure that the data meets certain quality standards by checking whether specific column values fall within a defined range. Each step is explained in detail, guiding you through the installation, setup, and validation process. By the end of the notebook, you'll understand how to use Great Expectations for data validation and quality assurance in your own datasets.


### Task 1:
- Download the [Great Expectations Task 1 Notebook](https://github.com/zubxxr/SOFE3980U-Lab5/blob/main/Great_Expectations_Task.ipynb) into a folder in your Google Drive.
- Follow the instructions in there and fill out the blanks.
- In your report, explain the three expectations you used and their relevance to the dataset.
- Download the notebook as a `.ipynb` file and upload it to your GitHub repository. Make sure all the output is shown.


## 2. CleanLab

CleanLab is a Python library designed for handling label noise in machine learning datasets. It provides tools for automatically detecting and correcting mislabeled data points, which are often a major source of error in supervised learning tasks.

Key Features:

    - Anomaly detection: Identifies potential anomalies in the dataset, such as mislabeled or incorrect data points.
    - Label correction: Uses statistical methods to predict the correct labels for data points that are likely mislabeled.
    - Integration: Seamlessly integrates with common machine learning frameworks, including Scikit-learn.

CleanLab can significantly improve model performance by reducing the impact of label noise, leading to more accurate and reliable machine learning models.


### Task 2:
- Download the [CleanLab Task 2 Notebook]() into a folder in your Google Drive.
- sadas
- asdasd
- Download the notebook as a `.ipynb` file and upload it to your GitHub repository. Make sure all the output is shown.



## Discussion
Compare accuracy, recall, and precision by describing the interpretation of each of them. Using examples shows applications in which one of them is more important than the others.

## Deliverables
1. A GitHub link of the code of the three tasks
2. Report about the discussion part and the results of the tasks.
