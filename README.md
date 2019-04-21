# Analyze-AB-Test-Results

## Project Overview
A/B tests are very commonly performed by data analysts and data scientists. In this project, we analyse and try to understand the results of an A/B test run by an e-commerce website and help the company take right decision on what should they implement.

The company has developed a new web page in order to try and increase the number of users who "convert," meaning the number of users who decide to pay for the company's product. Our goal is to work through this dataset to help the company understands if they should implement this new page, keep the old page, or perhaps run the experiment longer to make their decision.

## Data
We have the dataset that has 290584 unique users who have randomly been assigned the old or new landing page. We start with calculating few probabilities that will help us understand the dataset followed by the hypothesis testing on that. We also verify the results from hypothesis testing with the z-score results and futher apply Multiple Linear Regression.

Below are the data columns from the dataset used for analysis:
user_id     
timestamp
group - (control, treatment)
landing_page - (old, new)
converted - (1, 0)

## Install
This project requires Python 3.6 and the following Python libraries installed:

NumPy
Pandas
Matplotlib
Random
statsmodels.api
statsmodels.stats.proportion

You will also need to have software installed to run and execute a Jupyter Notebook

If you do not have Python installed yet, it is highly recommended that you install the Anaconda distribution of Python, which already has the above packages and more included. Make sure that you select Python 3.x installer.
