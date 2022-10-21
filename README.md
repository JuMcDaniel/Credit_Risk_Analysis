# Credit_Risk_Analysis

Overview of the analysis:
	The purpose of this analysis is to determine precision and recall through multiple learning models.  The overall goal is to determine the efficacy of the data for determining the credit risk of people for loan generation.  
  
  The six machine learning models includes:
    
    
        1.	Naïve Random Oversampling
        2.	SMOTE Oversampling
        3.	Under sampling
        4.	SMOTEENN random sampling
        5.	Balanced Random Forest Classifier
        6.	Easy Ensemble AdaBoost Classifier

Results:

      1.	Naïve Random Oversampling
          a.	Balance accuracy score: 62.3%
          b.	Precision: high risk- 0.01 which is low, low risk- 1.00 which is high
          c.	Recall score: high risk- 0.67 and low risk- 0.57
![image](https://user-images.githubusercontent.com/103297084/197223111-fa88aba0-8141-4d90-b27a-6f729ed06912.png)



      2.	SMOTE Oversampling
          a.	Balance accuracy score: 64.9%
          b.	Precision: high risk- 0.01 which is low, low risk- 1.00 which is high
          c.	Recall score: high risk- 0.63 and low risk- 0.36
          
![image](https://user-images.githubusercontent.com/103297084/197223388-7d09e6f2-c73e-4d9f-9ffd-9a36f9565020.png)

          

      3.	Undersampling
          a.	Balance accuracy score: 54.7%
          b.	Precision: high risk- 0.01 which is low, low risk- 1.00 which is high
          c.	Recall score: high risk- 0.68 and low risk- 0.41

![image](https://user-images.githubusercontent.com/103297084/197223737-03531155-87d5-467c-ab88-b2a5019e04a1.png)


      4.	SMOTEENN
          a.	Balance accuracy score: 63.0%
          b.	Precision: high risk- 0.01 which is low, low risk- 1.00 which is high
          c.	Recall score: high risk- 0.66 and low risk- 0.60

![image](https://user-images.githubusercontent.com/103297084/197223853-1c1f7b12-5556-463e-b563-d4d5a3e1b38c.png)


      5.	Balanced Random Forest Classifier
          a.	Balance accuracy score: 78.9%
          b.	Precision: high risk- 0.03 which is low, low risk- 1.00 which is high
          c.	Recall score: high risk- 0.70 and low risk- 0.87

![image](https://user-images.githubusercontent.com/103297084/197223960-47b8c322-b9de-4d75-bca0-4a558e97dfbd.png)


      6.	Easy Ensemble AdaBoost Classifier
          a.	Balance accuracy score: 93.1%
          b.	Precision: high risk- 0.09 which is low, low risk- 1.00 which is high
          c.	Recall score: high risk- 0.92 and low risk- 0.94
          
![image](https://user-images.githubusercontent.com/103297084/197224077-18d1c052-9b94-494c-80a1-0bfa4233626a.png)



Results:
	Overall, most of these learning models are similar with their outcomes with the data.  Overall, the precision is similar with the low risk credit reports being 1 in all the models determining that the model is good at predicting the low risk clients for loan determinate.  The model that is the most accurate is the AdaBoost Classifier with a balance accuracy score of 93% which is the highest compared to the other models that range from 54.7% -78.9%.  The best model for performing the data with would be the Easy Ensemble AdaBoost Classifier because it had the most accurate score and highest recall scores.  

