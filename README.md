# Titanic Big Data Project

## Project Overview
In this project, I analyzed the Titanic dataset using various data analysis and machine learning techniques. Below are the key steps and outputs of our project.

### Loading Data for Titanic
- Imported the dataset “Titanic.csv” and printed it.
- Filled in Null values (NAN values with 0 values) and removed data with null values.

### Exploratory Analysis
- Used `info()` to display data types, counts, and columns.
- Described the dataset using `describe()`, showing count, mean, standard deviation, minimum, and maximum values.
- Displayed the first ten rows and last ten rows of the dataset.
- Created scatter plots, box plots, and cat plots for various attributes like age, fare, gender, and class.

## Tools Used
- Google Colab
- TensorFlow
- Pandas
- NumPy

### Data Preprocessing
- Imported and prepared train and test datasets.
- Dropped irrelevant attributes (Ticket and Cabin) in both datasets.
- Created cross-tabulations for titles and genders.
- Mapped and created dummy variables for categorical columns like Title and Gender.
- Replaced NaN values in the age column with the mean age and categorized age groups.
- Replaced NaN values in the Embarked column with the mode value.
- Replaced NaN values in the Fare column with the median value and categorized Fare values.

<img width="444" alt="image" src="https://github.com/user-attachments/assets/2db71d70-2e5e-4f43-877e-eabd20a1bfa9">
<br><br>
<img width="465" alt="image" src="https://github.com/user-attachments/assets/c527b0ba-7c96-4181-8acc-943bfa15f3c0">
<br><br>
<img width="412" alt="image" src="https://github.com/user-attachments/assets/91a8e2cf-2f0f-4e8a-b00d-0bb16304ef44">
<br><br>
<img width="409" alt="image" src="https://github.com/user-attachments/assets/dea0c5aa-ffce-4015-964a-ebbddf34a45d">
<br><br>

### Model Training and Evaluation
- Trained models including Linear SVC, KNN Algorithm, Logistic Regression, and Decision Tree.
- Compared model accuracies:
  - Linear SVC: 66.62%
  - KNN Algorithm: 80.25%
  - Logistic Regression: 81.14%
  - Decision Tree: 100%

### Data Visualization
- Visualized survival rates by age and gender.
- Visualized the frequency of age and gender distribution.
- Analyzed survival rates with respect to the Embarked locations.

<img width="452" alt="image" src="https://github.com/user-attachments/assets/f0034a20-3acd-4ad4-a4aa-1fd68ca8e8f1">
<br><br>
<img width="452" alt="image" src="https://github.com/user-attachments/assets/4d5f2c1b-caba-449a-90bc-923c2a2b8912">
<br><br>
<img width="452" alt="image" src="https://github.com/user-attachments/assets/6dbcf065-9f57-4e9b-b1fe-d53721e055d2">
<br><br>
<img width="476" alt="image" src="https://github.com/user-attachments/assets/6439970d-e9f6-4b80-a112-f11b8a99add3">
<br><br>
<img width="452" alt="image" src="https://github.com/user-attachments/assets/ca2348b9-5e54-4d5d-9fa1-126dafd6561e">
<br><br>

## Conclusion
- The Decision Tree model showed the highest accuracy at 100%, making it the most reliable model for this dataset.
- Female passengers had a higher survival rate than male passengers.
- Embarked location influenced survival rates, with some locations having higher survival rates than others.
