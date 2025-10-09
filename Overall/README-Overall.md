# Overall


## Machine Learning (ML) Models:

The following ML classification models were implemented. Using a random sample of 50 records (without replacement), the SHAP values were calculated to determine the most influential features per model.

### K-Nearest Neighbours (KNN):

<img width="758" height="620" alt="EstObesity-SHAP-KNN" src="https://github.com/user-attachments/assets/a74260c7-77ca-45e4-9402-39dd51a0312c" />



### Support Vector Classification (SVC):



### Random Forest (RF):



### XGBoost (XGB):



For each model, the SHAP value was computed to determine which feature was most influential in correctly classifying obesity levels. The results for each model can be found in each script folder. 

To ensure consistent performance for varying data characteristics, the data used for training the models were randomly sampled without replacement. The degree of randomness also affects the final accuracy results and run times for each model.

As of October 8th, 2025, all models achieved accuracy results of over 80% with average run-times of under 3 minutes.

Moreover, to determine if the differences between male and female samples for specific features were statistically significant or due to random chance, hypothesis testing was performed (e.g: Student's t-Test). After testing, the results highlighted significant differences between male and female samples across several features. This suggests the need for additional Machine Learning models to classify Male and Female records separately. A significance level of 0.05 (5%) was used as it is the most commonly-used value in general hypothesis testing.

## References:

1. https://archive.ics.uci.edu/dataset/544/estimation+of+obesity+levels+based+on+eating+habits+and+physical+condition
2. https://www.semanticscholar.org/paper/Dataset-for-estimation-of-obesity-levels-based-on-Palechor-Manotas/35b40bacd2ffa9370885b7a3004d88995fd1d011

