# Obesity-Level-Estimation

The main purpose of this project was to categorize the obesity levels of 2,100+ individuals from Mexico, Peru and Colombia. This was achieved using several Machine Learning (ML) classification models; each  cross-validated and tuned to achieve optimal accuracy using appropriate hyperparameters.

Ultimately, the end goal was to determine how many people are overweight and/or obese as well as identify possible contributing factors leading to their current respective weight levels. Due to the inherent variance in the data, this was also achieved for Males and Females separately.

## Dataset:

The dataset used in this project was retrieved from the UCI Machine Learning Repository (see References below). In total, there are 2,111 records (1,068 male and 1,043 female). 

Additional information about each feature can be found in the "metadata.xlsx" file.

## Implementation:

Currently, the following classification models were implemented in this project:

- K-Nearest Neighbours (KNN)
- Support Vector Classification (SVC)
- Random Forest (RF)
- XGBoost (XGB) (excluding Male and Female scripts)

For each model, SHAP values was computed to determine which feature was most influential in correctly classifying obesity levels. The results for each model can be found in each script folder. 

To ensure consistent performance for varying data characteristics, the data used for training the models were randomly sampled without replacement. The degree of randomness also affects the final accuracy results and run times for each model.

As of October 8th, 2025, all models achieved accuracy results of over 80% with average run-times of under 3 minutes.

Moreover, to determine if the differences between male and female samples for specific features were statistically significant or due to random chance, hypothesis testing was performed (e.g: Student's t-Test). After testing, the results highlighted significant differences between male and female samples across several features. This suggests the need for additional Machine Learning models to classify Male and Female records separately. A significance level of 0.05 (5%) was used as it is the most commonly-used value in general hypothesis testing.

## Disclaimer:

For each script, neither the computed SHAP values nor the represented features for all models indicate the "true" causes for obesity. Additional external factors apart from those used in our dataset as well as further in-depth research over time is required to present a clearer picture on the obesity level results obtained.

Furthermore, the Machine Learning results obtained are only for illustration and data analytics purposes. No attempt should be made to utilize the same results and/or methodologies for classifying/predicting obesity levels for other personal uses.

## References:

1. https://archive.ics.uci.edu/dataset/544/estimation+of+obesity+levels+based+on+eating+habits+and+physical+condition
2. https://www.sciencedirect.com/science/article/pii/S2352340919306985?via%3Dihub
3. https://www.semanticscholar.org/paper/Dataset-for-estimation-of-obesity-levels-based-on-Palechor-Manotas/35b40bacd2ffa9370885b7a3004d88995fd1d011

