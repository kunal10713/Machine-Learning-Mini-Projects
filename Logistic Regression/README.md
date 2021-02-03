## Logistic Regression Project 

In this project we will be working with a advertising data set, indicating whether or not a particular internet user clicked on an Advertisement on a company website. We will try to create a model that will predict whether or not they will click on an ad based off the features of that user.

This data set contains the following features:

    * 'Daily Time Spent on Site': consumer time on site in minutes
    
    * 'Age': cutomer age in years
    
    * 'Area Income': Avg. Income of geographical area of consumer
    
    * 'Daily Internet Usage': Avg. minutes a day consumer is on the internet
    
    * 'Ad Topic Line': Headline of the advertisement
    
    * 'City': City of consumer
    
    * 'Male': Whether or not consumer was male
    
    * 'Country': Country of consumer
    
    * 'Timestamp': Time at which consumer clicked on Ad or closed window
    
    * 'Clicked on Ad': 0 or 1 indicated clicking on Ad
  
## Independent and dependent variables:

    X = ad_data[['Daily Time Spent on Site', 'Age', 'Area Income','Daily Internet Usage', 'Male']]
  
    y = ad_data['Clicked on Ad']
    
 ## Predictions and Evaluations:
   
    ### Confusion Matrix:
    
       * It is a performance measurement for machine learning classification problem where output can be two or more classes. 
       * Our Model results:
       
          [[ 156   6   ]
           [  25   143 ]]
            
    ### Classification_report:
    
      precision         recall      f1-score       support

          0             0.87          0.96          0.91       162
          1             0.96          0.86          0.91       168

      avg / total       0.91          0.91          0.91       330
      
     
## Precision vs. Recall:

  ### Precision:
  
    * Precision tells us how many of the correctly predicted cases actually turned out to be positive.
    * Precision is a useful metric in cases where False Positive is a higher concern than False Negatives.
    * Precision is important in music or video recommendation systems, e-commerce websites, etc. Wrong results could lead to customer churn and be harmful to the business.
    
    
  ### Recall:
  
    * Recall tells us how many of the actual positive cases we were able to predict correctly with our model.
    * Recall is a useful metric in cases where False Negative trumps False Positive.
    * Recall is important in medical cases where it doesn’t matter whether we raise a false alarm but the actual positive cases should not go undetected!
