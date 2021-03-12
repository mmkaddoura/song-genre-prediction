# Song Genre Prediction
Can we predict a song's genre using Spotify's audio features? 

# Who am I?
My name is Moh Kaddoura. I am a graduate student in the Master of Science in Data Science program at the University of San Francisco.

# What is this project?
Given 56,000 unique songs with 233,000 genre labels, I created a pipeline that appropriately transforms the data and successfully finds the best model with the best hyperparameters to solve this mullti-label classification problem. 

# Why is it important?
This project is important because it puts the data science process for a mullti-label classification problem in an interpretable pipeline. Multi-lablel classification is more complicated than multi-class classification because classes are not mutually exclusive in multi-label. Multi-label problems are all around us. Creating a pipeline is important becuase it ensures all preporcessing and modelling steps are fit and transformed when appropirate without the risk of forgetting a step or leaking data.

# What did I find?
The pieline found that best model is a Random Forest Classifier with specific hyperparameters. The model was sucessful with an F1 score of 0.67 and recall of 0.57.
