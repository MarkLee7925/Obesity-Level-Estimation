# Important Features per Model - Male records:

Using a random sample of 50 records (without replacement), the SHAP values were calculated to determine the most influential features (attributes) per model. These represent factors that could influence the obesity levels of all Male individuals in our dataset.

During the partition of training and test sets, a random state value of 1,000 was used to ensure the results are reproducible across multiple environments. However, results may vary depending on the set value.

## Machine Learning (ML) Models:

Below are the following ML classification models implemented along with their top 5 most important features:

### K-Nearest Neighbours (KNN):

<img width="755" height="459" alt="EstObesity-Male-SHAP-KNN" src="https://github.com/user-attachments/assets/10577777-11a0-4567-83d3-d6616735ad89" />

Top 5 most important features:
- Weight (Feature 2)
- Alcohol Consumption (Feature 6)
- Age (Feature 0)
- Main Meals per Day (Feature 4)
- Height (Feature 1)
  
### Support Vector Classification (SVC):

<img width="755" height="459" alt="EstObesity-Male-SHAP-SVC" src="https://github.com/user-attachments/assets/1b2e8fd9-45ec-4113-9c28-ec97a7d63d65" />

Top 5 most important features:  
- Weight (Feature 2)
- Height (Feature 1)
- Age (Feature 0)
- Transportation Mode (Feature 7)
- Alcohol Consumption (Feature 6)

### Random Forest (RF):

<img width="755" height="459" alt="EstObesity-Male-SHAP-RF" src="https://github.com/user-attachments/assets/7b6c91b3-579a-4636-b7c3-370fbaedb3d6" />

Top 5 most important features:
- Weight (Feature 2)
- Height (Feature 1)
- Age (Feature 0)
- Main Meals per Day (Feature 4)
- Alcohol Consumption (Feature 6)
