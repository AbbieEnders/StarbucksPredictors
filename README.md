# StarbucksPredictors
## Project Overview
- Starbucks collects data on offers and purchase transactions for their Rewards Members
- Will this data inform purchase transactions? Can we predict the transaction of a customer based on their demographic data?
- The expectation is that a classifier model will explore in the interaction in the app is able to be connected to the demographic data.
    - We will explore this success with the Accuracy, Precision, and F-1 score, as well as a confusion matrix with the withheld test dataset.
    - An F-1 score is great for classification because it allows us to evaluate precision and recall in one value. A better F-1 score means a more well performing model. 
- The regression model will determine if demographic data can predict the transaction amount.
    - For regression we can explore the R-squared score and residuals. This shows how much of the amount of the transaction isn't captured by the model for the test data.
## Where are the results?
Review a detailed review on Medium [add link].
## How do I use this?
You can download this notebook and see the code run.
### Dependencies
Versions of the packages in my virtual environment, starred ones called specifically in my project.

| Name   |                 Version|

matplotlib**              3.9.0  

matplotlib-inline**       0.1.7   

numpy**                   2.0.0    

pandas**                  2.2.2      

scikit-learn**            1.5.0                    

### Files in the repo
Starbucks_capstone_notebook.ipynb -> Jupyter Notebook used to analyze the mock-Starbucks user data.

data/portfolio.json-> offer information

data/profile.json-> user information

data/transcript.json-> interaction information
