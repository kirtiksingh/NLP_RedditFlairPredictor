# Reddit Flair Predictor: A NLP Project for CSD350 in Shiv Nadar University

## Pre-Requisites

**What are Reddit Flairs?**

A flair is a 'tag' that can be added to threads posted on the reddit website within a sub-reddit. They help users understand the category to which the posts they are scrolling through, belong and thus, help them filter out specific posts based on their preferences.

This is a mini web-app created with Flask that performs the task of predicting which flair should be alloted to a post. As a user, you just need to paste the link of the reddit post in the search bar. 

## Directory Structure 
 
* Notebooks:  1. Collecting 'India' subreddit data.ipynb : Data collection notebook
              2. Data Analysis.ipynb: Different Data Analysis Tasks and Model Development followed by Prediction
              
* requirements.txt: Containing the requirements need to run this project. 
* app.py : Contains the flask app
* inference.py : Inference Engine that runs the model and returns the predictions. 

## How to Run
 
* Fork/Download the project via GitHub              
* Navigate to the directory with requirements.txt, and open the terminal. This file contains the requirements need to run this project. 
* If you wish to create a virtual environment, you can follow steps given here. Else, run "pip install -r requirements.txt" in the terminal.
* Navigate to the directory with app.py, and run the file using python.

## Important
 
* Currently, this is only an Indian subreddit specific project, hence, all post links should be from https://www.reddit.com/r/india/ .
* Eg: https://www.reddit.com/r/india/comments/k9t5f1/too_much_democracy/ 

## References

https://towardsdatascience.com/scraping-reddit-data-1c0af3040768
https://github.com/prakharrathi25/reddit-flair-predictor/

