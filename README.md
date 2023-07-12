# Instagram-Reach-Analysis
Project Name: Data Analysis and Prediction using Passive Aggressive Regressor<br/>
This project involves data analysis and prediction using the Passive Aggressive Regressor model. The dataset consists of various features related to social media posts, and the goal is to predict the number of Impressions based on these features. The project has achieved an R2 score of 0.8307.<br/>

# Dataset Information
The dataset used for this project is a pandas DataFrame with the following columns:<br/>

Impressions: Number of impressions.<br/>
From Home: Number of impressions from the home feed.<br/>
From Hashtags: Number of impressions from hashtags.<br/>
From Explore: Number of impressions from the explore page.<br/>
From Other: Number of impressions from other sources.<br/>
Saves: Number of times the post was saved.<br/>
Comments: Number of comments on the post.<br/>
Shares: Number of shares the post received.<br/>
Likes: Number of likes the post received.<br/>
Profile Visits: Number of profile visits.<br/>
Follows: Number of follows.<br/>
Caption: Textual caption of the post.<br/>
Hashtags: List of hashtags used in the post.<br/>
The dataset contains 119 entries, and all columns have non-null values. The data types include 11 integer columns and 2 object columns.<br/>

# Project Summary
The main objective of this project is to analyze the given dataset and build a predictive model using the Passive Aggressive Regressor algorithm. The steps involved in the project are as follows:<br/>

Data preprocessing: The dataset is loaded into a pandas DataFrame, and initial exploratory data analysis is performed.<br/>
Feature engineering: The textual data in the Caption and Hashtags columns are processed to extract relevant features for the model.<br/>
Data visualization: Various visualizations are created to understand the relationships between the features and the target variable (Impressions).<br/>
Data splitting: The dataset is split into training and testing sets for model training and evaluation.<br/>
Model training: The Passive Aggressive Regressor model is trained on the training data.<br/>
Model evaluation: The trained model is evaluated using the R2 score, which is found to be 0.8307.<br/>
Prediction: The model is used to make predictions on new data.<br/>

# Dependencies
The following Python libraries are required to run this project:<br/>

pandas<br/>
scikit-learn<br/>
numpy<br/>
scikitlearn<br/>
matplotlib<br/>
plotly<br/>
wordcloud<br/>

# Instructions
To run this project, follow these steps:<br/>

Ensure that Python and the required libraries are installed on your system.<br/>
Download the project files and extract them to a directory.<br/>
Open a terminal or command prompt and navigate to the project directory.<br/>
Run the Python script data_analysis.py using the command: python data_analysis.py.<br/>
The script will load the dataset, perform data analysis, train the model, and generate predictions.<br/>
The results, including the R2 score, will be displayed in the console.<br/>
Feel free to modify the code or dataset as needed for your specific requirements. Enjoy exploring and analyzing the data!
