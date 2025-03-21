# Project - Disaster Response Pipeline 

## Summary
In this project, a machine learning pipeline is created to help classify messages sent during disaster events. This project aims to classify events into several categories to help forward disaster messages from people to the appropriate relief agency.

## Components
The different components of the project are 
- creating ETL pipeline that processes category and messages data and  merges, cleans, and stores it into SQlite database.
- creating Machine learning pipeline that loads the data from SQLite database, splits it into training and testing data, trains and tunes the model, and then shows results on testing data
- Web app extracts data from the database to provide data visualization and use the model to classify new messages into 36 categories

## How to run:
1. Run ETL pipeline for cleaning and storing in database - python data/process_data.py data/disaster_messages.csv data/disaster_categories.csv data/YourDatabaseName.db
2. Run ML pipeline that trains classifier - python models/train_classifier.py data/YourDatabaseName.db models/models.pkl
3. Run 'python run.py' command in the app's directory to run the web app. Click on Preview to open the web app
4. Type in any disaster message in the text box given. All the relevant categories will be highlighted in green by the model.


## Files

- ETL Pipeline Preparation.ipynb: This is the jupyter notebook in which python code is written to load two csv files messages.csv and categories.csv and merged them. The data is then cleaned and stored into SQlite database.
- ML Pipeline Preparation.ipynb: This is the jupyter notebook in which python code is written to load the data from SQLite database, splits it into training and testing data, trains and tunes the model and then shows results on testing data. The output is a pickle file containing the fitted model.
- disaster_messages.csv contains messages that were sent during disaster events - collected from Appen  (formerly Figure 8)) in csv format 
- disaster_categories.csv contains categories in csv format.
- process_data.py: This python script automates ETL Pipeline Preparation.ipynb jutyper notebook.
- train_classifier.py: This python script automates ML Pipeline Preparation.ipynb jutyper notebook.

## Outputs

![alt text](https://github.com/SakshamGupta55/Data-Scientist-Nanodegree-Udacity/blob/f15d74bae0cb920dd8204d178d3fd5e4a0a5da2a/Course%204%20-%20Project%20-%20Disaster%20Response%20Pipeline/Visualization-1.png)

![alt text](https://github.com/SakshamGupta55/Data-Scientist-Nanodegree-Udacity/blob/f15d74bae0cb920dd8204d178d3fd5e4a0a5da2a/Course%204%20-%20Project%20-%20Disaster%20Response%20Pipeline/Visualization-2.png)

![alt text](https://github.com/SakshamGupta55/Data-Scientist-Nanodegree-Udacity/blob/a93c848e4d925a954925179b3872b53d00920bf8/Course%204%20-%20Project%20-%20Disaster%20Response%20Pipeline/Screenshot%202.png)

![alt text](https://github.com/SakshamGupta55/Data-Scientist-Nanodegree-Udacity/blob/a93c848e4d925a954925179b3872b53d00920bf8/Course%204%20-%20Project%20-%20Disaster%20Response%20Pipeline/Screenshot%203.png)

![alt text](https://github.com/SakshamGupta55/Data-Scientist-Nanodegree-Udacity/blob/a93c848e4d925a954925179b3872b53d00920bf8/Course%204%20-%20Project%20-%20Disaster%20Response%20Pipeline/Screenshot%204.png)

![alt text](https://github.com/SakshamGupta55/Data-Scientist-Nanodegree-Udacity/blob/a93c848e4d925a954925179b3872b53d00920bf8/Course%204%20-%20Project%20-%20Disaster%20Response%20Pipeline/Screenshot%205.png)

![alt text](https://github.com/SakshamGupta55/Data-Scientist-Nanodegree-Udacity/blob/f15d74bae0cb920dd8204d178d3fd5e4a0a5da2a/Course%204%20-%20Project%20-%20Disaster%20Response%20Pipeline/IDE_latest.PNG)

## License and Acknowledgement
This is completed as part of the Udacity Data Scientist Nanodegree.
