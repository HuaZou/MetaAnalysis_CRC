## Meta-analysis on human gut microbiota in Colorectal Cancer 



![](https://raw.githubusercontent.com/HuaZou/Image_Host/main/img/20210929091843.png)



**Steps**:

1. Data Partition into Discovery set and Replication set
2. Performing Differential Analysis on Discovery Set using wilcox rank-sum test or t test if the data distribution of each feature meets Gaussian distribution or not
3. Removing multicollinearity of features
4. Splitting Discovery set into TrainSet and TestSet with 0.8 probability 
5. Feature selection by Recursive feature elimination
6. Building Random Forest model with tuning parameters 
7. Determining the optimal model through the ROC or Accuracy (mostly used when the counts of groups are not balanced)
8. Validating the optimal model based on the Replication set 



### Contributors

1. [Hua Zou](zouhua1@outlook.com)

   