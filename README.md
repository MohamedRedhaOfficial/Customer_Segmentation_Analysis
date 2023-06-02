# Customer Segmentation Analysis
Analysis project for dividing the customers based on their purchase history, income, age, interest,so that the store can get help in
personalized marketing and provide customers with relevant deals.

# Preprocessing
- Dropped rows with missing values
- Extracted dates and created new features from them
- Dropped outliers by setting a cap on Age and income.
- Label encoding the categorical features
- Scaled the features using the standard scaler
- Created a subset dataframe for dimensionality reduction

# Dimensionality Reduction
![dimensionreduc](https://github.com/MohamedRedhaOfficial/Customer_Segmentation_Analysis/assets/126083924/c30ccf86-0e7c-4a82-b981-91560a054393)

# CLUSTERING
Elbow Method to determine the number of clusters to be formed
![kmeanelbow](https://github.com/MohamedRedhaOfficial/Customer_Segmentation_Analysis/assets/126083924/1d4586f8-3dc4-400c-91bb-c33faafa5f5c)

The above figure indicates that four will be an optimal number of clusters for this data.

# Plotting the clusters
![clustersplot](https://github.com/MohamedRedhaOfficial/Customer_Segmentation_Analysis/assets/126083924/e1fb1995-0bce-43fb-b971-f5ef451be990)

# Evaluating Models
![clusterdistrib](https://github.com/MohamedRedhaOfficial/Customer_Segmentation_Analysis/assets/126083924/61a280b0-6913-414e-8096-9c7ea6ad2888)
![clusterprofile](https://github.com/MohamedRedhaOfficial/Customer_Segmentation_Analysis/assets/126083924/d58546f6-3e8d-4736-824a-bb9d7e8f1530)

Income vs spending plot shows the clusters pattern

    group 0: high spending & average income
    group 1: high spending & high income
    group 2: low spending & low income
    group 3: low spending & low income
    
# Profiling Summary
![clustergroups](https://github.com/MohamedRedhaOfficial/Customer_Segmentation_Analysis/assets/126083924/44b98993-1da9-4779-acb7-91e9da1aed88)
