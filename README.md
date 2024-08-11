### **Objective:** To predict loan defaults using a variety of machine learning techniques, with a focus on optimizing metrics like ROC AUC and model accuracy.

# Key Approaches:
### 1. Data Preprocessing:

- **Missing Value Handling:** Replaced missing values in binary columns with 0 for False and 1 for True. 

- **Feature Scaling:** Applied normalization techniques (e.g., StandardScaler) to ensure that all features contributed equally to the model.

- **Categorical Encoding:** Utilized Label Encoding and One-Hot Encoding to convert categorical features into a suitable format for model training.

### 2. Feature Selection:

- **Manual Feature Selection:** Selected numerical and categorical features based on domain knowledge and importance in predictive modeling.

- **SMOTE & SMOTE Tomek Links:** Applied these techniques to address class imbalance, thereby improving the model’s ability to accurately predict the minority class.

### 3. Modeling:

#### **Random Forest Classifier:** 

- Developed a baseline model using the Random Forest algorithm.

- Manually fine-tuned hyperparameters like n_estimators, max_depth, min_samples_split, min_samples_leaf, and max_features to improve performance.

- Focused on optimizing for the ROC AUC metric to enhance the model’s ability to discriminate between loan defaulters and non-defaulters.

### 4.Model Evaluation:

- **Accuracy & Classification Report:** Achieved an accuracy of 0.92, with balanced precision, recall, and F1-scores across both classes.

- **Confusion Matrix:** Visualized the model's performance through a confusion matrix to understand the true positives, true negatives, false positives, and false negatives.

- **ROC AUC Score:** Calculated and analyzed the ROC AUC score to assess the model’s performance across different threshold values, ensuring robust class separation.

### 5.Visualizations:

- **Feature Importance:** Plotted feature importances to identify which features contributed most to the predictions.

- **ROC Curve:** Plotted the ROC curve to visualize the trade-off between the true positive rate and the false positive rate.

  ## **Results:**
   ### Final Model Performance:
  -  Accuracy: 0.92
  -  ROC AUC Score: 0.98
  -  Achieved a balanced and robust model capable of accurately predicting loan defaults.
  
## **Tools & Technologies Used:**
-  **Programming Languages:** Python
-  **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
-  **Machine Learning Techniques:** Random Forest, SMOTE, SMOTE Tomek Links, Hyperparameter Tuning
