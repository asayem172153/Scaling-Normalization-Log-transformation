# Scaling-Normalization-Log-transformation loop and also using built in libraries 
Here some of **DATA Pre-processing** techniques are intoduced
- Scaling: Scaling refers to the process of standardizing or normalizing the numerical features of your dataset. It's often used to bring all the features to a similar scale or range, typically between 0 and 1 or with a mean of 0 and a standard deviation of 1. Common methods for scaling include Min-Max scaling and Z-score scaling (Standardization).

- Normalization: Normalization is a specific type of scaling that typically refers to scaling features to have a mean of 0 and a standard deviation of 1. This makes the data follow a normal distribution (bell curve), which can be useful in some machine learning algorithms.

- Log Transformation: Log transformation is a technique used to change the distribution of data, often applied to data that is highly skewed or contains outliers. Taking the logarithm of the data can make it more normally distributed, which can improve the performance of certain models. It's especially useful when dealing with data that varies over several orders of magnitude.
- Robust Scaler: Robust Scaler, as the name suggests, is designed to be robust to outliers. It scales the features by removing the median and dividing by the interquartile range (the difference between the 75th and 25th percentiles).  
Robust Scaler is a good choice when your data contains outliers that can significantly affect other scaling techniques. It helps mitigate the impact of outliers and is less sensitive to their presence.
- MaxAbsoluteScaler: MaxAbsoluteScaler scales the features by dividing them by the maximum absolute value within each feature. This transformation brings all feature values within the range of -1 to 1, preserving the sign of the data.  
It's particularly useful when you have features with very large outliers or when you want to preserve the direction of the data but scale it to a specific range.  
