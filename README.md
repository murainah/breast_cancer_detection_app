# Breast Cancer Detection Web Application

<img src="output.jpeg" >

## A Web Application to predict Breast Cancer using SVM  (Deployed on Render)




#### Working link: (Deployed on Render) https://breast-cancer-detect.onrender.com/

### 1.Project Requirements or Dependencies
* Anaconda Python (to get ML Libraries)
* Pip install flask (For Front-end)

### 2. Load Dataset
Breast Cancer Wisconsin (Diagnostic) Original Data Set

Attribute Information:
1.	Sample code number: ID number
2.	Clump Thickness:1-10
3.	Uniformity of Cell size:1-10
4.	Uniformity of Cell shape:1-10
5.	Marginal Adhesion:1-10
6.	Single Epithelial Cell Size:1-10
7.	Bare Nuclei:1-10
8.	Bland Chromatin:1-10
9.	Normal Nucleoli:1-10
10.	Mitoses:1-10
11.	Class: (2 for Benign, 4 for Malignant)
### 3.Build and Train the model using SVM
Using SVM (Support Vector Machines) we build and train a model using human cell records, and classify cells to predict whether the samples are benign or malignant.
### 4.Flask Creation
Python app.py
http://127.0.0.1:5000/

1.	Breast_Cancer_Detection.ipynb — This contains code for the machine learning model to predict cancer based on the class.
2.	app.py — This contains Flask APIs that receives cells details through GUI or API calls, computes the predicted value based on our model and returns it
3.	templates & static  — This folders contains the HTML template and CSS styling to allow user to enter cells details and displays the predicted output.



