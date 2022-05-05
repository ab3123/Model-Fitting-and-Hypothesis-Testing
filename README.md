# Model-Fitting-and-Hypothesis-Testing

Which model(s) do you think would be most appropriate and why?
* Here in this project we have use three models and they are Multiple Liner Regression , KNN Classification and Decision Tree classification .
* The most preferable model among this three is KNN Classification ass it is giving accuracy of 91% to predict our targeted column i.e positions.

 Identify the model that performs the best and try to answer why it performed that well?
 
 ### Conclusion
* 1. Player reactions and composure increase overall performance most.
* 2. With ~91% accuracy we can predict players position just knowing physical and technical features.
* 3. The various accuracies of this three models are as follows - 
     * Multiple Liner Regression - 
         * r2 socre is  0.8182423905862364
         * mean_sqrd_error is== 8.567424701975897
         * root_mean_squared error of is== 2.927016348088254

     * KNN Classification - 
         * Accuracy: 0.909366391184573
          
     * Decision Tree classification - 
         * Accuracy: 0.8424242424242424 
         
* 4. The KNN Model Performs better because , when we first perform the KNN on the data so it gives only 86% accuracy, But when we try to find the error rate for different number neighbors (K) . So we get to know that around 8 or 9 neighbors error rate is reaching plateau so that's we  perform again classification algorith with n_neighbors where error rate was smallest . i.e which we took 9 and that's why the model is predicting with 91% accuracy and we can say this as an best model for our problem.         
