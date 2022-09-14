# [Project 1: Data Science Meets Cybersecurity](https://github.com/kelvinsima2/Cybersecurity-Data-Science)
- The main aim of this project is to conduct a comparison study of different machine learning algorithms used to detect cyber attacks using several datasets and evaluation metrics. In this project, the CICIDS2017, CICDDoS2019 and the NSL-KDD datasets were investigated.
- One of the main challenges facing anomaly detection is the high rate of false alarms. The best ML algorithm for detecting cyberattacks was therefore investigated.
- Decision Tree classifier performed the best in terms of both accuracy and speed in detecting cyber attacks in a multi-class context using the CICIDS2017 and CICDDoS2019 datasets. Using the CICIDS2017 dataset, the Decision Tree classifier had an accuracy score of 99% and an average training time of 0.029s. Using the CICDDoS2019 dataset, the Decision Tree classifier had an accuracy score of 95% and an average training time of 0.025s. 
- The Naive Bayes classifier performed the best in detecting attacks in a binary context using the NSL-KDD Dataset. An accuracy score of 80% and an average test time of 0.006s was achieved.
- The code for the CICIDS2017 dataset can be found [here](https://github.com/kelvinsima2/Cybersecurity-Data-Science/blob/main/Notebooks/CICIDS2017_Data_Science_Project.ipynb).
- The code for the CICDDoS2019 dataset can be found [here](https://github.com/kelvinsima2/Cybersecurity-Data-Science/blob/main/Notebooks/CICDDoS2019_Data_Science_Project.ipynb).
- The code for the NSL-KDD dataset can be found [here](https://github.com/kelvinsima2/Cybersecurity-Data-Science/blob/main/Notebooks/NSL_KDD_Data_Science_Project.ipynb).


# [Project 2: Predicting Drivers' Coupon Acceptance](https://github.com/kelvinsima2/coupon_predictor/blob/main/Coursework1.ipynb)

- This project involves the use of the in-vehicle coupon recommendation dataset available on the UCI machine learning repository to predict whether a driver would accept a coupon based on various conditions.
- SVM, KNN, Decision Tree and AdaBoost classification models were evaluated to determine which model was most accurate in the predictions.
- For each classification algorithm, hyperparameters were tuned to achieve maximum performance.
- The SVM algorithm had the highest accuracy and F1 score, making it the best model.
- The full written report for the project can be found [here](https://github.com/kelvinsima2/coupon_predictor/blob/main/report_F134712.pdf).


# [Project 3: Hate Speech Detector](https://github.com/kelvinsima2/Hate-Speech-Detector/blob/main/notebooks/Hate_Speech_Detector.ipynb)
- The main aim of this project is detecting subtle hate-speech in a sentence. The data used was obtained from [Microsoft's TOXIGEN dataset](https://github.com/microsoft/TOXIGEN).
- The model aims to detect subtle hate against ethnicity, sexual orientation, gender and disability.
- A convolutional neural network (CNN) model was used, and accuracies of 100% were achieved using the test data.
- This model is still under development. More data is needed to detect crude hate speech.

# [Project 4: Student Results Monitoring System](https://github.com/kelvinsima2/Student-Results)
- This project involves the use of students' [test results](https://github.com/kelvinsima2/Student-Results/blob/main/TestResultCSV%20files.zip) obtained from the 20COP504 module at Loughborough University. Data collected from students that rated the [difficulty of the module](https://github.com/kelvinsima2/Student-Results/blob/main/StudentRate.csv) was also used.
- The test results data was cleaned, formatted and stored in a database using a [Jupyter Notebook in Python](https://github.com/kelvinsima2/Student-Results/blob/main/CW1.ipynb).
- Python modules that obtained an individual student's [test results](https://github.com/kelvinsima2/Student-Results/blob/main/testResults.py), analyzed [student performance](https://github.com/kelvinsima2/Student-Results/blob/main/studentPerformance.py) as well as identifying [underperforming](https://github.com/kelvinsima2/Student-Results/blob/main/underperformingStudent.py) and [hardworking](https://github.com/kelvinsima2/Student-Results/blob/main/hardworkingStudents.py) students were developed.
- A python [main program](https://github.com/kelvinsima2/Student-Results/blob/main/menu.py) which provided the required menu options to the module leader for the program functionalities was created using the tkinter library. 

# [Project 5: Baseball Games Data Analysis](https://github.com/kelvinsima2/Baseball_teams_analysis_R_project/blob/main/baseball%20project.Rmd)
- This project involved using several datasets about American baseball from the R package 'Lahman'. It is adapted from Loughborough University's 21MAP501 Coursework.
- A simple linear regression model was developed in order to predict the logarithm (base 10) of mean salaries of baseball teams. This is showm in Figure 2.
- A multiple regression model was developed to predict the number of runs made by a player based on features such as player age, height, team, year, position and number of hits.
- Finally a lasso regression model for logistic regression was explored in order to predict division winners. The sum of specificity and sensitivity was between 1.79 and 1.87 for all 3 divisions, indicating that the prediction was almost equally good across all divisions.
- The pdf of the knitted R notebook can be found [here](https://github.com/kelvinsima2/Baseball_teams_analysis_R_project/blob/main/Baseball%20Project.pdf)


