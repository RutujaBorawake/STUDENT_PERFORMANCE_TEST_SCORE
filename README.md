## END TO END MACHINE LEARNING PROJECT ##

- This project understands how the student's performance (test scores) is affected by other variables such as Gender, Ethnicity, Parental level of education, Lunch and Test preparation course.

## Data Collection ##
- Dataset Source - https://www.kaggle.com/datasets/spscientist/students-performance-in-exams?datasetId=74977
- The data consists of 8 column and 1000 rows.

# Dataset Information #
- gender : sex of students  -> (Male/female)
- race/ethnicity : ethnicity of students -> (Group A, B,C, D,E)
- parental level of education : parents' final education ->(bachelor's degree,some college,master's degree,associate's degree,high school)
- lunch : having lunch before test (standard or free/reduced) 
- test preparation course : complete or not complete before test
- math score
- reading score
- writing score

Use of various classification models like Liner Regression, Decision Tree, Random Forest, XGBoost, MLPClassifier was done. Linear regression was selected as best model from above. The linear regression model provided 87% accuracy in training. Testing accuracy for model was 88%. 80% data was used for training and 20% data was used for testing. After Providing various details the model will predict the math score for student.

## Software Requirements ##
Python 3.10.7
Visual Studio Code
Git Cli
Jupyter Notebook
AWS account
GitHub account

## Life cycle of Machine learning Project ##

- Understanding the Problem Statement
- Data Collection
- Data Checks to perform
- Exploratory data analysis
- Data Pre-Processing
- Model Training
- Choose best model
