
# Udacity Nanodegree Course 6- Starbucks Project

## Project Overview and Motivation
In this project, analysis of Starbucks customers is performed to determine which demographic groups respond best to which offer type. Moreover, a machine learning model is used to predict if the customer will react positively to the offers sent and make purchases because of the offers sent.
Starbucks periodically sends promotions to users and they generally fall into three categories:
- BOGO (Buy-One-Get-One Free): Users must make a purchase that meets a certain spending requirement to receive a reward equal to a specified threshold.
- Discount Offers: These provide a reward based on a percentage of the amount spent.
- Informational Offers: These are purely promotional and do not include any spending requirement or associated reward.

## Library used:
1. Pandas
2. Numpy
3. Matplotlib
4. sklearn
5. json
6. XGboost
7. pickle
8. seaborn
9. time


## Files
- Starbucks_Capstone_notebook.ipynb: This is the jupyter notebook in which python code is written to analysis of Starbuscks customer and to predict how customer will respond to the offers sent using machine learning technique
- Folder - data :
  - portfolio.json - containing offer ids and data about each offer
  - transcript.json - records for transactions, offers received, offers viewed, and offers completed
  - profile.json - demographic data for each customer
  - analysis_data_final.csv - Data created for analysis
  - final_data.csv - Final data used in machine learning models
- Outputs
  - Analysis - Contains screenshot of all analysis
  - Output - Machine learning model output

## Run
In a terminal or command window, navigate to the project directory (that contains this README) and run the following command:

ipython Starbucks_Capstone_Notebook.ipynb

## Dataset used
Starbucks data consists of 3 tables that provides information about the user demographics, offer details, and the user event log.
- portfolio.json
- profile.json
- transcript.json 

## Results summary and Output

Results and detail discussion is published on [Medium](https://medium.com/@markhu1990b/brewing-insights-decoding-starbucks-offers-with-machine-learning-991e1012a9cf)

Various analysis of the customers is done to understand customer demographics and behaviour. Some analysis are as follows:

| ![Image1](https://github.com/SakshamGupta55/Udacity-Nanodegree-Course6--Project-Data-Scientist-Capstone/blob/9f98b145d34dbbf3efde8ebb6e440ab41116cb5c/Outputs/Analysis/1%20Age1.png) | ![Image2](https://github.com/SakshamGupta55/Udacity-Nanodegree-Course6--Project-Data-Scientist-Capstone/blob/111e3d2f43555fe727a5ee704b73816a79e7070d/Outputs/Analysis/1%20Age2.png) |
|---|---|

| ![Image1](https://github.com/SakshamGupta55/Udacity-Nanodegree-Course6--Project-Data-Scientist-Capstone/blob/cf0c92cf722f584f778b8e981b82853af0ea882d/Outputs/Analysis/2%20Income1.png) | ![Image2](https://github.com/SakshamGupta55/Udacity-Nanodegree-Course6--Project-Data-Scientist-Capstone/blob/cf0c92cf722f584f778b8e981b82853af0ea882d/Outputs/Analysis/2%20Income2.png) |
|---|---|

| ![Image1](https://github.com/SakshamGupta55/Udacity-Nanodegree-Course6--Project-Data-Scientist-Capstone/blob/cf64fa75f82ec00bebb676e9e1334a84206cc809/Outputs/Analysis/3%20gender1.png) | ![Image2](https://github.com/SakshamGupta55/Udacity-Nanodegree-Course6--Project-Data-Scientist-Capstone/blob/cf64fa75f82ec00bebb676e9e1334a84206cc809/Outputs/Analysis/3%20gender2.png) |
|---|---|

| ![Image1](https://github.com/SakshamGupta55/Udacity-Nanodegree-Course6--Project-Data-Scientist-Capstone/blob/cf64fa75f82ec00bebb676e9e1334a84206cc809/Outputs/Analysis/4%20Offer%20type1.png) | ![Image2](https://github.com/SakshamGupta55/Udacity-Nanodegree-Course6--Project-Data-Scientist-Capstone/blob/cf64fa75f82ec00bebb676e9e1334a84206cc809/Outputs/Analysis/4%20Offer%20type2.png) |
|---|---|

Machine learning output : 

| Metric             | Logistic Regression | Decision Tree | Random Forest | Gradient Boosting | XGBoost  | Random Forest Optimisation |
|--------------------|---------------------|---------------|---------------|-------------------|----------|---------|
| Train Accuracy     | 59.2%               | 94.4%         | 94.4%         | 60.2%             | 69.3%    | 94.2%   |
| Train Precision    | 57.9%               | 91.2%         | 90.8%         | 58.7%             | 67.0%    | 90.8%   |
| Train Recall       | 67.3%               | 98.2%         | 98.8%         | 69.0%             | 76.0%    | 98.3%   |
| Test Accuracy      | 59.0%               | 79.5%         | 82.8%         | 60.1%             | 64.5%    | 83.0%   |
| Test Precision     | 57.9%               | 74.0%         | 77.6%         | 58.7%             | 62.3%    | 78.0%   |
| Test Recall        | 67.1%               | 90.9%         | 92.4%         | 68.8%             | 71.4%    | 91.2%   |

![alt text](https://github.com/SakshamGupta55/Udacity-Nanodegree-Course6--Project-Data-Scientist-Capstone/blob/51fde2b60665c14e1ef6b51a0ab21d8c3a40c136/Outputs/Output/ROC%20curve.png)

![alt text](https://github.com/SakshamGupta55/Udacity-Nanodegree-Course6--Project-Data-Scientist-Capstone/blob/51fde2b60665c14e1ef6b51a0ab21d8c3a40c136/Outputs/Output/Top%20Features.png)


## License and Acknowledgement
This is completed as part of the Udacity Data Scientist Nanodegree. Thank you Starbucks for providing the dataset.

