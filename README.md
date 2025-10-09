# Obesity-Level-Estimation

The main purpose of this Machine Learning classification project is to categorize the obesity levels of 2,100+ people using multi-class classification methodologies. This was achieved using four different classification models; each were cross-validated and tuned to achieve optimal accuracy using appropriate hyperparameters.

Ultimately, the end goal is to determine how many people are overweight and/or obese as well as identify possible contributing factors leading to their current respective weight levels. Due to the inherent variance in the data, this was also achieved for Males and Females separately.

## Dataset:

The dataset used in this project was retrieved from the UCI Machine Learning Repository (see References below). In total, there are 2,111 records; each representing a single individual. Out of all records, 1,068 were male whereas 1,043 were female. 

Additional information about each feature can be found in the "metadata.xlsx" file.

## Implementation:

Currently, the following classification models were implemented in this project:

- K-Nearest Neighbours (KNN)
- Support Vector Machine - Classification (SVC)
- Random Forest (RF)
- XGBoost (XGB) (excluding Male and Female scripts)

For each model, the SHAP value was computed to determine which feature was most influential in correctly classifying obesity levels. The results for each model can be found in each script folder. 

To ensure consistent performance for varying data characteristics, the data used for training the models were randomly sampled without replacement. The degree of randomness also affects the final accuracy results and run times for each model.

As of October 8th, 2025, all models achieved accuracy results of over 80% with average run-times of under 3 minutes each.

Moreover, in order to determine if the differences between male and female samples for specific features are statistically significant or due to random chance, hypothesis testing was performed (e.g: Student's t-Test). After analysis, the results highlighted significant differences between male and female samples across many features thereby suggesting the need for additional Machine Learning scripts to classify Male and Female records separately. A significance level of 0.05 (5%) was used as it is the most relevant and most common value in general hypothesis testing.

## References:

1. https://archive.ics.uci.edu/dataset/544/estimation+of+obesity+levels+based+on+eating+habits+and+physical+condition
2. https://www.semanticscholar.org/paper/Dataset-for-estimation-of-obesity-levels-based-on-Palechor-Manotas/35b40bacd2ffa9370885b7a3004d88995fd1d011

