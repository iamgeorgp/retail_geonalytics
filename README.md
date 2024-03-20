# Project Retail Success Prediction
Welcome to the Retail Success Prediction project! This project aims to predict the success score of retail objects using geospatial data and additional features.

### Files Description:
features.py: This file contains the code for generating additional features from the provided datasets. It merges the main training data with the additional features based on geographic coordinates.

train.py: In this file, the machine learning model is trained using the preprocessed training data. It utilizes the RandomForestRegressor algorithm and evaluates the model's performance using Mean Absolute Error.

solution.py: Here, the trained model is used to generate predictions for the test data. The predictions are saved in a submission file in the required format.

submission.csv: This file contains the predicted scores for the test data, following the format specified in the sample submission file.

README.md: You are reading it right now! This file provides an overview of the project, file descriptions, and instructions for running the code.

### Running the Code:
To run the code, follow these steps:

- Ensure that you have Python installed on your system.
- Clone this repository to your local machine.
- Install the required libraries by running pip install -r requirements.txt.
- Place the provided datasets (train.csv, test.csv, features.csv) in the same directory as the code files.
- Run the features.py script to generate additional features.
- Execute the train.py script to train the machine learning model.
- Finally, run the solution.py script to generate predictions for the test data.

### Dataset:

- train.csv: Training data containing the unique identifiers, latitude, longitude, and success scores of retail objects.
- test.csv: Test data with similar structure to the training data, without the success scores.
- features.csv: Additional features including geographic coordinates and other location-based attributes.
- Please note that the exact details of the features have been omitted for confidentiality reasons.
