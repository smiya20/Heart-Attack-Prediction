# Heart-Attack-Prediction
To predict whether a person will suffer from heart attack or not.
# Objectives
To predict the probability of suffering of any patient from heart attacks in the upcoming future.  
To exploit machine learning techniques on medical data set to assist in the prediction of heart attack.           
Identify the major factors influencing heart attack. 
# Dataset
The dataset is taken from kaggle, https://www.kaggle.com/rashikrahmanpritom/heart-attack-analysis-prediction-dataset

Here we have the description of the features:                                    
age - age in years                                          
sex - sex (0 = female; 1 = male)                            
cp - chest pain type (1 = typical angina; 2 = atypical angina; 3 = non-anginal pain; 0 = asymptomatic)           
trtbps - resting blood pressure (in mm Hg on admission to the hospital)            
chol - serum cholestoral in mg/dl            
fbs - fasting blood sugar > 120 mg/dl (0 = false; 1 = true)            
restecg - resting electrocardiographic results (0 = normal; 1 = hypertrophy; 2 = having ST-T wave abnormality)        
thalachh - maximum heart rate achieved          
exng - exercise induced angina (0 = no; 1 = yes)                         
oldpeak - ST depression induced by exercise relative to rest                       
slp - the slope of the peak exercise ST segment (0 = downsloping; 1 = flat; 2 = upsloping)              
caa - number of major vessels (0-4)             
thall - thallium stress test (1 = fixed defect; 2 = reversable defect; 3 = normal)                
output - 0 = less chance of heart attack; 1 = more chance of heart attack            
# Methodologies
1. Dataset collection
2. Performed EDA  : Handled Outliers , Deleted duplicate rows, visualization and Feature scaling.  
3. Created 7 different Classification Models : Logistic Regression, KNN, Decision Tree, SVM, Random Forest, Navie Bayes, XGBoost.
4. Performed comparative analysis on the techniques used.

# Visualization

![image](https://user-images.githubusercontent.com/95580124/156506149-5e4ea264-2896-493d-8ece-8c73f2557fa5.png)

![image](https://user-images.githubusercontent.com/95580124/156709823-65af0b4c-068b-48f0-80d4-797d80a5029c.png)

![image](https://user-images.githubusercontent.com/95580124/156709840-c8e5d6dc-9291-462a-9531-ccd59cbb8596.png)


# Libraries used
1. Data Cleaning: numpy, pandas
2. Visualisation: seaborn, matplotlib
3. Feature scaling: MinMaxScaler
4. Splitting to train and test: train_test_split
5. Accuracy calculation & confusion matixs: metrics,confusion_matrix,accuracy_score,precision_score,recall_score,f1_score
6. Algorithms: DecisionTreeClassifier, RandomForestClassifier, svm, KNeighborsClassifier, LogisticRegression, GaussianNB, XGBClassifier


