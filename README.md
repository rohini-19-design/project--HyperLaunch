# project--HyperLaunch
 Project Title:
           Student Placement Prediction Using Random Forest Classifier

Objective:
         To predict whether a student will be placed or not placed using academic scores and other features, by training a machine learning model using Random Forest, a powerful ensemble classification algorithm.

Dataset Overview:
        Dataset contains records of students including their education background and placement outcomes.
Target Variable: status (Placed / Not Placed)

Key Features:

Column	Description:
     1. CGPA - It is the overall grades achieved by the student.
     2. Internships - It tells the number of internships a student has done.
     3.Projects - Number of projects a student has done.
     4.Workshops/Certifications - As there are multiple courses available online student opt for them to upskill themselves.
     5.ApptitudeTestScore - Aptitude test are generally a part of the recruitment process to understand the Quant and logical thinking of the student.
     6.SoftSkillrating - Communication is a key role that plays in the placement or in any aspect of the life.
     7.ExtraCurricularActivities - This helps provide and insight about the personality of an individual regarding how much he is active other than the academic.
     8.PlacementTraining - It is provided to students in college to ace the placement process.
     9.SSC and HSC - Senior Secondary and Higher Secondary Marks.
     10.PlacementStatus - This is our target column with two classes placed and not placed.
Technologies Used:
 
 •	Programming Language: Python
 •	Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
 •	Machine Learning Model: Random Forest Classifier

 ML Model Used:

Random Forest Classifier
  •	An ensemble method that uses multiple decision trees.
  •	Provides better accuracy and handles non-linear data well.

 Steps in the Project:
  
  •	Load and explore the dataset:
    The dataset is loaded using pandas.read_csv() and examined with basic functions like df.head() and df.info().
  •	Clean the data (handle nulls, encode categories):
     1.	Missing values are handled using df.fillna() and duplicates are removed with df.drop_duplicates().
     2.	Some columns are encoded for categorical data and scaled where necessary.

•	Split the data into training and test sets:
    1.	The dataset is split into training and testing sets using train_test_split().
    2.	A machine learning model, such as logistic regression or decision tree, is trained and evaluated.

•	Train the Random Forest Classifier
•	Predict placement status
•	Evaluate the model:
        The model was evaluated using the following metrics:
•	Accuracy: Measures how often the model correctly predicted the placement status.
•	Confusion Matrix: A matrix showing the performance of the classification model, with counts of true positives, false positives, true negatives, and false negatives.
•	Classification Report: Includes additional metrics like precision, recall, and RMSE

Result:
The Random Forest Classifier achieved an accuracy of **79%** on the test data.

