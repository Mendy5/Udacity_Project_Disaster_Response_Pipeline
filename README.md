# Udacity Data Scientist Project II: Udacity_Project_Disaster_Response_Pipeline
This repository contains all related files of the Udacity data scientist nanoprogram project II: Disaster_Response_Pipeline

## Installation
The code should run in the Python 3.6.* environment

## Data source
[Figure Eight](https://www.figure-eight.com/)

## Project Motivation
This project is for building an ETL and Machine Learning pipelines to classifiy the messages from some disasters to the right genre. The genre is important for different disaster professionals and can help them to find the messages they care about faster.

## File Description
There are 4 directories in this repository.
1. app: This directories contains the application of final results, which are visualization and search features on web pages. The framework is flask and the model is from classifier.pkl.
2. data: This direcotory contains the source files and the ETL pipeline, which extract, transform and load source data to a table in the DisasterResponse.db.
3. models: This direcotory has a classification model. Classify data from DisasterResponse.db to multiple targerts. And the final results contain in the classifier.pkl.

## Results
The final application is a webpage. The page has a search feature and a bar chart. The bar chart shows the count of message of each genre. And the search feature classifies the searched text to the predicted genre.

How to get the webpage
1. go to the app direcotory
2. run `python run.py`
3. Go to http://0.0.0.0:3001/

# Licensing, Authors, Acknowledgements
Must give credit to Figure Eight for the data. You can more information about [Figure Eight here](https://www.figure-eight.com/).
