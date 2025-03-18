# Student Placement Prediction

#### The goal of this project is to build a machine learning model that predicts whether a student will be placed (1) or not placed (0) based on their CGPA (Cumulative Grade 
  Point Average) and IQ score. The dataset contains 100 samples with three features: cgpa, iq, and placement (target variable).

#### The dataset consists of the following columns:

##### 1) Unnamed: 0: An index column (can be dropped).

##### 2) cgpa: The student's CGPA (ranges from 4.3 to 7.4).

##### 3) iq: The student's IQ score (ranges from 42 to 200).

##### 4) placement: The target variable (1 = placed, 0 = not placed).


####  Data Preprocessing

##### 1) Drop the Unnamed: 0 column as it is unnecessary.

##### 2) Check for missing values and handle them if any.

##### 3) Normalize or standardize the features (cgpa and iq) if required.

##### 4) Split the dataset into training and testing sets (e.g., 80% training, 20% testing).

####  Exploratory Data Analysis (EDA)

##### 1) Visualize the distribution of cgpa and iq using histograms or boxplots.

##### 2) Create a scatter plot to observe the relationship between cgpa, iq, and placement.

##### 3) Check for class imbalance in the target variable (placement).

####  Feature Selection

##### Use cgpa and iq as input features.

##### placement is the target variable.

####  Model Selection

##### Choose a classification algorithm i'll used Logistic Regression:

#### Logistic Regression

##### Train the model on the training dataset.

#### Model Evaluation

##### Evaluate the model using metrics such as:

##### Accuracy

#### Visualization of Decision Boundaries

##### Use the plot_decision_regions function from the mlxtend library to visualize the decision boundaries of the trained model.

#### Deployment

##### Save the trained model using or pickle.



