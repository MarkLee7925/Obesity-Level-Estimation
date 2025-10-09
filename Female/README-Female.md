# Important Features per Model - Female records:

Using a random sample of 50 records (without replacement), the SHAP values were calculated to determine the most influential features (attributes) per model. These represent factors that could influence the obesity levels of all Female individuals in our dataset.

During the partition of training and test sets, a random state value of 1,000 was used to ensure the results are reproducible across multiple environments. However, results may vary depending on the set value.

## Machine Learning (ML) Models:

Below are the following ML classification models implemented along with their top 5 most important features:

### K-Nearest Neighbours (KNN):

<img width="755" height="459" alt="EstObesity-Female-SHAP-KNN" src="https://github.com/user-attachments/assets/2e59e91f-ac6f-46a7-871f-29a68e525888" />
  
Top 5 most important features:
- Weight (Feature 2)
- Height (Feature 1)
- Food Between Meals (Feature 5)
- Age (Feature 0)
- Overweight History (Feature 3)
  
### Support Vector Classification (SVC):

<img width="755" height="459" alt="EstObesity-Female-SHAP-SVC" src="https://github.com/user-attachments/assets/05560468-06b8-42f5-a462-cdeb73139616" />

Top 5 most important features:  
- Weight (Feature 2)
- Height (Feature 1)
- Transportation Mode (Feature 7)
- Overweight History (Feature 3)
- High Caloric Foods (Feature 4)

### Random Forest (RF):

<img width="755" height="459" alt="EstObesity-Female-SHAP-RF" src="https://github.com/user-attachments/assets/6276e934-c09f-42ee-80bd-48a0c19453bd" />

Top 5 most important features:
- Weight (Feature 2)
- Height (Feature 1)
- Overweight History (Feature 3)
- Food Between Meals (Feature 5)
- High Caloric Foods (Feature 4)
