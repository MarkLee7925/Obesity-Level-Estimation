# Important Features per Model:

Using a random sample of 50 records (without replacement), the SHAP values were calculated to determine the most influential features (attributes) per model. These represent factors that could influence the obesity levels of all represented individuals in our dataset.

During the partition of training and test sets, a random state value of 42 was used to ensure the results are reproducible across multiple environments. However, results may vary depending on the set value.

## List of Features:

0. Gender
1. Age
2. Height
3. Weight
4. Overweight History
5. High Caloric Foods
6. Vegetables in Meals 
7. Main Meals per Day
8. Food Between Meals
9. Smoking
10. Water Consumption
11. Monitor Calories
12. Physical Activity
13. Time on Tech Devices
14. Alcohol Consumption
15. Transportation Mode

## Machine Learning (ML) Models:

Below are the following ML classification models implemented along with their top 5 most important features:

### K-Nearest Neighbours (KNN):

<img width="758" height="620" alt="EstObesity-SHAP-KNN" src="https://github.com/user-attachments/assets/a74260c7-77ca-45e4-9402-39dd51a0312c" />

Top 5 most important features:
- Overweight History (Feature 4)
- Weight (Feature 3)
- Water Consumption (Feature 10)
- Main Meals per Day (Feature 7)
- Gender (Feature 0)
  
### Support Vector Classification (SVC):

<img width="758" height="620" alt="EstObesity-SHAP-SVC" src="https://github.com/user-attachments/assets/e376b959-2a59-48fb-b066-2215645f080b" />

Top 5 most important features:
- Weight (Feature 3)
- Height (Feature 2)
- Gender (Feature 0)
- Age (Feature 1)
- Vegetables in Meals (Feature 6)

### Random Forest (RF):

<img width="758" height="620" alt="EstObesity-SHAP-RF" src="https://github.com/user-attachments/assets/f2817abe-49ab-4a52-a8d2-8eeacc5eb95e" />

Top 5 most important features:
- Weight (Feature 3)
- Height (Feature 2)
- Age (Feature 1)
- Vegetables in Meals (Feature 6)
- Gender (Feature 0)

### XGBoost (XGB):

<img width="758" height="620" alt="EstObesity-SHAP-XGB" src="https://github.com/user-attachments/assets/d1f768b1-f92a-4bd7-b19e-857ac8412674" />

Top 5 most important features:
- Weight (Feature 3)
- Height (Feature 2)
- Gender (Feature 0)
- Vegetables in Meals (Feature 6)
- Food Between Meals (Feature 8)


