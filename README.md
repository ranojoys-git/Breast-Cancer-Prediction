# About the dataset:

The dataset contains 569 rows and 32 columns. the columns are categorized into three diffrent kinds:
- Mean Features: Describe the average characteristics of nuclei.
- Standard Error (SE) Features: Measure the variability or dispersion of the features.
- Worst Features: Capture the most extreme or severe values, often critical for distinguishing malignant tumors.

# Steps involved:

**Exploratory Data Analysis (EDA):**
Exploratory data analysis was performed to understand the dataset better. This included checking for missing values, analyzing the distribution of features, and visualizing the data using pairplots and boxplots to identify patterns and relationships.

**Data Preprocessing:**
The dataset was split into training and testing sets using train_test_split from sklearn.model_selection. This ensures that the model is evaluated on unseen data. The features were standardized using StandardScaler to normalize the data for better model performance.

**Model Selection and Training:**
The following algorithms were used for classification:

- Logistic Regression
- Decision Tree
- Random Forest Classifier

**Model Evaluation:**
The models' performance was evaluated on the test dataset using metrics such as accuracy and classification report. The models achieved high accuracy in classifying the malignant and benign samples.
