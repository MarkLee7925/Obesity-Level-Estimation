# Obesity-Level-Estimation

The main purpose of this Machine Learning classification project is to categorize the obesity levels of 2,100+ records using multi-class classification methodologies. This was achieved using four different classification models. Each model was cross-validated and tuned to achieve optimal accuracy using appropriate hyperparameters.

Ultimately, the end goal is to determine how many individuals are overweight and/or obese as well as identifying contributing factors. Due to the inherent variance in the data, this was also achieved for Males and Females separately.

## Dataset:

The dataset used in this project was retrieved from the UCI Machine Learning Repository (see References below). In total, there are 2,111 records; each representing a single individual. Out of all records, 1,068 are male whereas 1,043 are female. 

Additional information about each feature can be found in the "metadata.xlsx" file.

## Implementation:

Currently, the following classification models were implemented in this project:

- K-Nearest Neighbours (KNN)
- Support Vector Machine - Classification (SVC)
- Random Forest (RF)
- XGBoost (XGB) (excluding Male and Female scripts)

To ensure consistent performance for varying data characteristics, the data used for training the models were randomly sampled without replacement.

Moreover, in order to determine if the differences between male and female samples for specific features are statistically significant or due to random chance, hypothesis testing was performed (e.g: Student's t-Test). These results highlighted the need for additional Machine Learning scripts to classify Male and Female records separately.

## References:

1. https://archive.ics.uci.edu/dataset/544/estimation+of+obesity+levels+based+on+eating+habits+and+physical+condition
2. https://www.semanticscholar.org/paper/Dataset-for-estimation-of-obesity-levels-based-on-Palechor-Manotas/35b40bacd2ffa9370885b7a3004d88995fd1d011

