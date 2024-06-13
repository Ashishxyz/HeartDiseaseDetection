#### Objective
To develop a predictive model for heart disease using machine learning techniques and achieve high accuracy in classification.

#### Dataset
- **Source**: Kaggle
- **Content**: The dataset includes various health indicators and the target variable indicating the presence or absence of heart disease.

#### Steps Involved

1. **Dataset Extraction**:
   - The dataset is downloaded from Kaggle using the API.

2. **Data Preprocessing**:
   - Handling missing values.
   - Encoding categorical variables.
   - Splitting the data into training and testing sets.

3. **Model Building**:
   - **Decision Tree**:
     - **Parameters**: `min_split=30`, `max_depth=8`
     - Characteristics: Simple, interpretable, may struggle with complex relationships.
   
   - **Random Forest**:
     - **Parameter**: `min_samples_split=10`
     - Characteristics: Ensemble method, better generalization, reduces overfitting.
   
   - **XGBoost**:
     - Characteristics: High performance, efficient, handles complex interactions well.

4. **Model Evaluation**:
   - Models are compared based on their performance metrics such as accuracy, precision, recall, and F1-score.
   - **Key Result**: Achieved a high accuracy of 99.7%, indicating excellent model performance.

#### Conclusion
- **Decision Tree**: Offers simplicity and interpretability but may not handle complex patterns effectively.
- **Random Forest**: Provides better robustness and accuracy through ensemble learning.
- **XGBoost**: Delivers the best performance due to its advanced boosting techniques and efficiency.
