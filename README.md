# Research-practice
Worked on Random forest regression model, Leave one out cross validation and Support vector machine
**Leave one out cross validation:**
The LOOCV method is utilized to assess the accuracy of machine learning algorithms in predicting data that was not employed to develop the model. 
While it produces a dependable and impartial appraisal of the model's performance, it can be resource-intensive to implement. Even though it is 
user-friendly and does not require any configuration settings, there are situations where this technique should be avoided, such as when dealing 
with large datasets or complex models that are computationally expensive to evaluate.

**Implementation:**
The existing solution for the dataset was processed by random forest regression model, so to get more optimized result I have tried implementing and processsing
the dataset in LOOCV model. Which inturn gave good result.

**Result:**
below shown is the result of one of the datapoints
(actual y)
visc
0.821
0.7883
0.7705
0.7735
0.7762
0.7852
0.8063
0.8384
0.8609
0.921
0.9931

(Predicted y)
0.7883					
0.5685					
0.7797					
0.7774					
0.776	   mean square error train: 0.009740333585858586				
0.7744	 mean absolute error train: 0.05753636363636365				
0.8104					
0.8609					
0.8384					
0.949					
0.9009					






