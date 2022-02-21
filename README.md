# Credit_Risk_Analysis

## Overiview 
Jill and I are tasked with applying machine learning to solve a real-world challenge: credit card risk. Credit risk is an inherently unbalanced classification problem, with using a credit card data set from LendingClub we will oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, you’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, you’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk.

## results 

![image](https://user-images.githubusercontent.com/92553694/154877583-f62feff1-d7a6-479b-b55a-3d3e0d3b7726.png)

Looking here we can see the balanced accuracy score (66%) and the precision (99%) and recall scores (60%) for the Naive Random Oversampling.

![image](https://user-images.githubusercontent.com/92553694/154878490-6276073c-e20e-432a-9af5-fcfc232191cc.png)

Looking here we can see the balanced accuracy score (66%) and the precision (99%) and recall scores (70%) for SMOTE Oversampling.

![image](https://user-images.githubusercontent.com/92553694/154878621-4095ed5f-c592-4e3a-af81-5bedbee967c2.png)

Looking here we can see the balanced accuracy score (54%) and the precision (99%) and recall scores (40%) for Undersampling.

![image](https://user-images.githubusercontent.com/92553694/154878730-ccd00d38-c18c-4b7f-a089-cbb142f1172d.png)

Looking here we can see the balanced accuracy score (64%) and the precision (99%) and recall scores (59%) for Combination Sampling.

![image](https://user-images.githubusercontent.com/92553694/154878806-45f6065e-815f-4b18-8642-135c7e8c7618.png)

Looking here we can see the balanced accuracy score (79%) and the precision (99%) and recall scores (87%) for Balanced Random Forest Classifier.

![image](https://user-images.githubusercontent.com/92553694/154879033-25a17325-80d5-4934-afe1-9ba64d13c0d4.png)

Looking here we can see the balanced accuracy score (93%) and the precision (99%) and recall scores (93%) for AdaBoost Sampling.

## Summary 
Based on the analysis and testing it seems as if AdaBoost performed the best across the metrics. They key metric that it performed best on was recall. AdaBoost preformed the best in the average of all metrics and caught 93% of the fraud cases however it still lacks precision which is a distinguishing factor in uncovering all of these cases. While there may be some flaws in AdaBoost, it seems like it is the best model for our data in order to catch the most fraud claims.
