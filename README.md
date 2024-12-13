# A Quest for Heart Attack Prediction
## AI Bootcamp: Project Two

### Group Members
* Matthew Dlugosz
* Madeline Jankowski
* Katia Monteros
* Manali Patel 

<img src="https://www.nm.org//-/media/northwestern/healthbeat/images/medical-advances/how-artificial-intelligence-is-saving-lives-heart-failure_ft.jpg" alt="Alt Text" width="800" height="350">

### Project Overview
**Aim:**
This project aims to train a machine learning model on a dataset to predict the risk of having a heart attack. 

**Hypothesis:**
We predicted that the studied traditional and risk-enhancing features would be the leading predictors in our machine learning model and could keening assess one’s risk for having a heart attack.

Traditional Risk Factors:
* Increasing age
* Smoking
* Diabetes
* High Blood Pressure
* High Cholesterol
* Obesity
* Male gender
  
Risk Enhancing Factors:
* Family history of early CVD
* High risk ethnicity
* Higher than normal tryiglycerides

### Dataset Overview
The 'Heart Attack Risk Prediction Dataset' contains medical information of 8,763 patients and has 26 columns. It covers a range of factors that may contribute to heart attacks, including patient details, medical history, lifestyle factors, and socioeconomic factors. 

The target column, 'Heart Attack Risk', is a binary classification variable that indicates whether a patient is at risk for a heart attack:
* 1 = Yes
* 0 = No

<img src="https://github.com/user-attachments/assets/a58e91f9-ee3f-47a1-a047-f596e7616a17" alt="Image description" width="400" height="300">

Data Sources - The 'Heart Attack Risk Prediction Dataset' is a synthetic dataset generated using ChatGPT, which may introduce bias and could impact the model's accuracy scores.

### Approach to Project Goals 
This project compares the performance of various machine learning models based on the following metrics: 
* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC Curve

The machine learning models tested in this project were:
* Logistic Regression
* Random Forest Classifier
* Decision Tree Classifier
* XG Boost
* Gradient Boost
* Support Vector Machine (SVM)
* K-Nearest Neighbors (KNN)

### Results
After testing various machine learning models and assessing their effectiveness in predicting heart attack risk, 'Logistic Regression' was determined to be the top performing model, achieving and overall model accuracy of 64.2%.

* The model correctly predicted 5624 instances of Class 0 (true negatives)
* The model correctly predicted 0 instances of Class 1

This suggests the model always predicts Class 0 and fails to identify Class 1. 

### Conclusion
...
### Future Development Plan
...
### Instructions to Run the Code
1. Clone the Repository
* Open terminal on the local machine and run the following command:
  
```git clone https://github.com/maddiejane25/Project-2.git```

2. Set Up Environment
* Make sure Python is installed on the computer
* Open terminal on the local machine and run the following commands:

```cd Project-2```

3. Run the Code
* Open the project folder in an IDE (Jupyter Notebook, Google Colab or VSCode)
* Import necessary files
* Start running the code

### Slideshow
[Slideshow ](https://docs.google.com/presentation/d/1g0D8h2mI9JEUH5VGRzRVXbHPKNpetEnNND75WcOhGws/edit?usp=sharing)

### Citations
Banerjee, Sourav. “Heart Attack Risk Prediction Dataset.” Kaggle, 11 May 2024, www.kaggle.com/datasets/iamsouravbanerjee/heart-attack-prediction-dataset/data. 

