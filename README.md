***Churn Analysis Project (Telecom Industry)***

**Situation :**  
Analyzed customer churn within the telecom industry to identify key drivers and predict future churners for targeted retention efforts.

**Task :**  
Developed a churn analysis dashboard to provide insights into customer behaviour and predict churn risk.

**Action :**  
Data Acquisition & Transformation :-   
Utilized Microsoft SQL Server to build a database architecture for customer data.    
Extracted and loaded customer information from source files & created SQL views to transform data for analysis.    
Machine Learning Model Development :-  
Employed Python and Jupyter Notebook to build a Random Forest model for churn prediction.   
Trained and tested the model on customer data subsets.  
Power BI Dashboard Construction :-  
Designed a comprehensive dashboard in Power BI to visualize churn metrics, customer profiles, and churn prediction results.  

**Result :**  
Delivered a churn analysis dashboard that facilitated :-  
Churn Driver Identification: Uncovered key factors influencing customer churn.  
Predictive Churn Risk Assessment: Identified potential future churners for targeted retention campaigns.    
Data-Driven Marketing Strategies: Enabled development of targeted marketing campaigns to improve customer retention.    

*From the given confusion matrix and classification report, here's what can be inferred:*  
**Confusion Matrix:**  
True Negatives (TN) = 785: The model correctly classified 785 samples as class 0 (negative class).  
False Positives (FP) = 62: The model incorrectly classified 62 samples as class 1 when they were actually class 0.  
False Negatives (FN) = 136: The model incorrectly classified 136 samples as class 0 when they were actually class 1.  
True Positives (TP) = 219: The model correctly classified 219 samples as class 1 (positive class).  

**Classification Report:**  

Class 0 (Negative Class):  
Precision = 0.85: Out of all the instances predicted as class 0, 85% were actually class 0.  
Recall = 0.93: Out of all the actual class 0 instances, the model correctly identified 93%.  
F1-score = 0.89: This is the harmonic mean of precision and recall, showing a good balance between them.  

Class 1 (Positive Class):  
Precision = 0.78: Out of all the instances predicted as class 1, 78% were actually class 1.  
Recall = 0.62: Out of all the actual class 1 instances, the model correctly identified 62%.  
F1-score = 0.69: This is lower than for class 0, indicating that the model struggles more with class 1.  

***Overall Metrics:***  
Accuracy = 0.84: The model correctly classified 84% of all instances.  
Macro avg: Averages precision, recall, and F1 across both classes equally (i.e., without considering the class imbalance).  
Weighted avg: Takes into account the support (number of instances) for each class when calculating averages, reflecting that there are more class 0 instances than class 1.  

***Key Observations:***  
The model performs significantly better on class 0 (the negative class), as evidenced by higher recall and F1-score for class 0.  
Class 1 (the positive class) has a lower recall (62%), meaning the model misses quite a few positive instances.  
Precision for both classes is relatively high, but the imbalance between recall scores suggests the model is better at identifying class 0 than class 1.  

**Inference:** 
The model has good overall accuracy (84%) but struggles to recall positive instances, which may need addressing, especially if class 1 is critical in the context of the problem (e.g., fraud detection, where missing positive cases can be costly).  

*Kindly click on this link to check out the dashboard* : https://tinyurl.com/hmrcjeaj  

![Screenshot (1450)](https://github.com/user-attachments/assets/88f28855-0782-427e-b384-21e2f2a7b961)
![Screenshot (1451)](https://github.com/user-attachments/assets/ad0c0b20-0a3c-49cc-b7f5-75fe14db96af)

*Credits (YT tutorial)* : https://tinyurl.com/3yz9fpna
