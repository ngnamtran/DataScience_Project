# DataScience_Project

## Introduction
  This project aims to analyze the student performance in exams by using linear regression and distribution, and predicting how students perform for each object. This project will be helpful for teachers in high school to keep track of their students, and the subjects that the student performs in class. Therefore, the teacher can take further action for each student.
The main point of the project is analyzing the factors that can affect student scores, and if we can predict the student's score by factors. There are three questions that this project concentrates:
  1. Does food affect the student score? If students receive the standard lunch, do they receive higher scores?
  2. Which group of race/ethnicity has the highest average score? In this group, male or female has the higher score?
  3. Can we predict their score based on the parental level of education and what is the percentage of the accuracy?

## Selection of Dataset
  The model processing and training are using a Jupyter Notebook with Python language  and are available in this repository's “code” folder. The data has 1000 high school students in the United States with 8 characteristics including: 
-  gender (female, male), 
-  race/ethnicity(group A, group B, group C, group D, group E)
-  parental level education (some highschool, highschool, some college, associate’s degree, bachelor’s degree, master’s degree)
-  lunch (standard, free/reduced)
-  test preparation course ( none, completed) 
-  math score [0,100]
-  reading core [17,100]
-  writing score [10,100]
  The dataset can be found on [Royce Kimmons website](http://roycekimmons.com/tools/generated_data/exams). Otherwise, you can find on [Kaggle](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams/data).
This is the data preview of the first 5 students in the dataset:
![Original Data Preview](/Graphs/orig_data_preview.png)
  In this data, I use the average score for analysis. The column "average score" is calculated from the average of math scores, writing scores, and reading scores of each student.
![Add Average Score](/Graphs/avg_score_data.png)
  In order to reduce the mistakes in processing data, I check if the data have any duplicates or null values in the dataset:
![Check Data]
### Methods
-  NumPy, and Pandas for data analysis distribution and analysis
-  Matplot, Seaborn for graphs
-  Scikit-learn for data analysis and predicting
-  GitHub to upload the project
-  Jupyter Book as IDE
   
