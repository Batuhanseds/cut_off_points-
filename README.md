# cut_off_points-
In Binary classification models our goal is predicting right class for each data point. After taking data and preparation for the model, we focus on model success. When we finish the model, Is the task completed?  
No : we must focus on chose the threshold value, we can't give 0.5 for default.  


The other way you can try all thresholds for best accuracy. 
Sometimes one class is more important than other, for an example when we are predicting cancer or non-cancer. Like these use cases, we can change thresholds for better predictions not for maximum accuracy. And like these life and death issues, is it right to predict all data? If we are not sure must we predict? Can be another third answer like that "I am not sure"?    

Steps:
1.	Creating Data Points and models
2.	Find threshold with ROC Curve and use geometric means and F1
3.	Find threshold with weight
4.	Find cut of points to predict
