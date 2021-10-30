# Heart_Disease_Prediction_ML

#### By <a href="https://www.linkedin.com/in/priyankaroy07/">Priyanka Roy</a>
<br>

This is a Heart Disease Data Set, collected from the UCI Machine Learning Repository. The complete collection consists of four individual databases collected from four different institutions located in Cleveland, Hungary, Switzerland, and the VA Long Beach. This database contains 76 attributes, but all published experiments refer to using a subset of 14 of them. In particular, the Cleveland database is the only one that has been used by ML researchers to
this date. The "goal" field refers to the presence of heart disease in the patient. <br> <br>

<h3>Features of this dataset:</h3> 

* <b>age</b>: person's age in years
* <b>sex</b>: person's sex- 1 for male and 0 for female
* <b>cp</b>: chest pain type (4 values)- typical angina, atypical angina, non-anginal pain, asymptomatic
* <b>trestbps</b>: resting blood pressure
* <b>chol</b>: serum cholestoral in mg/dl
* <b>fbs</b>: fasting blood sugar > 120 mg/dl (1- T ; 0- F)
* <b>testecg</b>: resting electrocardiographic results where, 0 = normal, 1 = having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV) and 2 = showing probable or definite left ventricular hypertrophy by Estes' criteria
* <b>thalach</b>: maximum heart rate achieved
* <b>exang</b>: exercise induced angina
* <b>oldpeak</b>: oldpeak = ST depression induced by exercise relative to rest
* <b>slope</b>: the slope of the peak exercise ST segment (1 = upsloping, 2 = flat, 3 = downsloping)
* <b>ca</b>: number of major vessels (0-3) colored by flourosopy
* <b>thal</b>: 3 = normal; 6 = fixed defect; 7 = reversable defect
* <b>hd</b>: heart disease, which is our <b>target variable</b> (0 = no, 1 = yes).

<br><h3>Main Objective(s):</h3> 

   * Explaining the features and target variable
   * Deal with the missing values
   * Performing One-hot Encoding
   * Splitting the dataset into 80% training and 20% for testing. Adding random state and stratification
   * Training with Decision Tree Classification
   * Tree diagram of the Decision Tree
   * Showing the Confusion Matrix, Classification report, and ROC-AUC &
   * Determining the accuracy of the ML model
   * Explaining the model

<br><h3>Observation(s)/Outcome Analysis:</h3>

   * The recall rate is about <b>93%</b> , that is, still 7% of the patients who has heart disease will be diagnosed wrong. But as of now, it's good enough to continue. <br>
   * If the AUC is in the range of 0.5~1, that means the model has value of prediction. The higher the score is, the better the model is. Moreover, the model will be a perfect classifier if the AUC equals to one. We got almost <b>0.9</b> of the AUC score, not bad at all! <br>
   * This model has an accuracy of <b>88.33%</b> (with random state= 63 as we found some variations with different state no. but this is the highest accuracy state) which explains that while dealing with the dataset this model is preety handy because we know, when the accuracy rate of a model > 85% we can call that model good enough. Although, many more ML algorithms might result more fruitful considering a better accuracy rate which could be explored later. <br>

<br> <a href="https://archive.ics.uci.edu/ml/datasets/heart+disease"> <h3>Dataset Reference: Click Here</h3> </a> <br>

