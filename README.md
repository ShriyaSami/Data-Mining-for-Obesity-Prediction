# Data Mining for Obesity Prediction
**This project applies data mining techniques to address a real-world problem. The real-world problem at hand is the prediction of obesity levels of individuals based on variables such as lifestyle and physical factors. The code for this is available in the Obesity Prediction Code.R file.**

## Dataset Identification  
Chosen Dataset: Estimation of Obesity Levels Based on Eating Habits and Physical Condition via UCI Machine Learning Repository, consisting of 17 attributes and 2111 records.  

## Data Pre-Processing  
Data pre-processing involved:  
•	Rounding values to remove leading digits.
•	Feature encoding (one-hot encoding. dummy encoding and label encoding).

## Machine Learning 
- **Data Pre-processing:** feature encoding (one-hot encoding, dummy encoding and label encoding), rounding values to remove leading digits.
- **Machine Learning Models Used:** K-Nearest Neighbour (KNN), Decision Tree, Random Forest. 
- **Model Comparison:**

| Model | Accuracy | Specificity | Sensitivity |
| --- | --- | --- | --- |
| Decision Tree | 0.83 | 0.94 | 0.86 |
| Random Forest | 0.97 | 1 | 0.98 |
| KNN | 0.81 | 0.96 | 0.73 |  

Overall, the random forest classifier performed the best at correctly predicting overweight individuals. This is as it achieved the best accuracy as well as the best sensitivity (true positives), which is more appropriate within the healthcare domain. This demonstrates that machine learning models can play a significant role in the healthcare domain to identify individuals with obesity to provide targeted interventions. 
