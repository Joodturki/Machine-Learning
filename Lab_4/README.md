Lab Summary

In this lab, I explored the dataset and applied several basic data preprocessing steps.

First, I inspected the dataset using df.info() and df.isnull().sum() to understand the structure and check for missing values. The dataset contains 2000 rows and no missing values were found.

To practice handling missing data, I intentionally introduced some missing values and then filled them using the mean of the Area column.

Next, I checked for outliers in the Price column using the IQR method. After calculating the lower and upper bounds, I found that all values were within
the acceptable range, so no outliers needed to be removed.

Then, I applied Min-Max normalization and Z-score standardization to scale the numerical features.

Finally, I checked the correlation between numerical features. The results showed very weak relationships between them, so applying PCA was not necessary for this dataset.

