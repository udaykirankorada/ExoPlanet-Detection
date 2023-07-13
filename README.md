# ExoPlanet-Detection

## Introduction
Detection of exoplanets is an important step in understanding the expanse of life forms across solar systems different from ours. In this project, we use open-source data available from the Kepler Space Telescope (KST) and machine learning methods to detect exoplanets.

## Methodology
The idea is to plot the intensities of different stars at different times. When the transit curve is plotted, we expect an intensity drop whenever the exoplanet makes a transit. The data is filtered and trained using ML to predict whether a given time series data belongs to an exoplanet system or not.

## Working
Basic Python libraries are used to perform preliminary analysis on the '.csv' file of the data. Afterward, the data is filtered and used to train the ML model. Afterward, the model is used to make predictions for the test dataset.

# Libraries
Python libraries: 
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Sklearn
- SciPy

Filters used:
- Median filter
- Savgol filter

ML model: Random Forest Classifier

## Results
Accuracy of above 90% is seen for both the train and test datasets.

## Impact
This project is a demonstration of the fact that even with widely freely available software and easily understandable libraries, one can perform a significant amount of analysis with astronomical data.

## Instructions
1. Download the train dataset and test dataset from these links.
- Train dataset (https://drive.google.com/file/d/19eXeuOLqCqhy-C66W-QFbv0NmdUPzwNX/view?usp=drivesdk)
- Test dataset (https://drive.google.com/file/d/19RbrLDdu5kYTZHac_lnYH8DNJFZgrsXj/view?usp=drivesdk)
2. Open the Python file and set the path of the read.csv command and run the code.

