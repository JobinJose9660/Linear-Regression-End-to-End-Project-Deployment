# Linear Regression -End To End Project with Azure Deployment

This project is linear Regression program which predicts the admission for collage program
This project uses a dataset from Kaggle to predict the chances of the
admission of a student into foreign universities based on different evaluation criteria.
This tries to explain the concepts simply, extensively, and thoroughly to approach
the problem from scratch and then its deployment to a cloud environment.

#
Machine Learning with Deployment to Azure Cloud Platform .

##
The Problem statement: 
The goal here is to find the chance of admission of a candidate based on his/her GRE Score (out of 340), TOEFL Score (out of 120), rating of the University (out of 5) in which he/she is trying to get admission, Strength of the SOP (out of 5), strength of the Letter Of Recommendation (out of 5), CGPA (out of 10) and the research experience (0 or 1).

#### Application Design: 
Once we have the data source fixed, the machine learning approach majorly consists of two pipelines:
The Training Pipeline -The training pipeline includes data pre-processing, selecting the right algorithm for creating the machine learning model, checking the accuracy of the created model and then saving the model file.

### The Testing Pipeline 
Once the training is completed, we need to expose the trained model as an API for the user to consume it. For prediction, the saved model is loaded first and then the predictions are made using it. thensame app is deployed to the  AZURE cloud platform.

## Data Set Information
- <class 'pandas.core.frame.DataFrame'>
- RangeIndex: 400 entries, 0 to 399
- Data columns (total 9 columns):
 -#   Column             Non-Null Count  Dtype  
----  ------             --------------  -----  
 -   Serial No.         -  400 non-null    int64  
 -    GRE Score         -  400 non-null    int64  
 -   TOEFL Score        -  400 non-null    int64  
 -   University Rating  -  400 non-null    int64  
 -   SOP                -  400 non-null    float64
 -   LOR                -  400 non-null    float64
 -   CGPA               -  400 non-null    float64
 -  Research           -   400 non-null    int64  
 -   Chance of Admit    -  400 non-null    float64
- dtypes: float64(4), int64(5)
- memory usage: 28.2 KB


## Softwares used 
- Python 
- Pycharm
- Flask API
- Azure
- Github
- HTML
## Libraries and Algorithms
- Pandas
- Matplot.lib
- Linear Regression
- Pickle
