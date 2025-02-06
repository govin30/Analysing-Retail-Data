The retail industry is evolving rapidly, with competition driving the need for data-driven decision-making. Leveraging data analytics allows retailers to gain valuable insights into customer behavior, product performance, and transaction trends, ena-bling them to enhance customer satisfaction and drive profitability. Retailers increas-ingly rely on customer intelligence to predict future behaviors, optimize inventory, and design personalized marketing strategies.

The objective of the assignment are as follows;
1)	To employ data cleaning techniques for improved retail data quality
2)	To examine the complexity in the data for optimal dimensionality
3)	To visualize the pre-processed data and identify patterns between attributes

Data Cleaning
1) Missing Values - Missing values has been screened and they have been replaced with the mode since the they were categorical data
2) Negative Values - There could be no negative value on the total amount and they were converted into positives. Negative values indicated items being returned
3) Duplicated rows - Both the duplicated rows were deleted as one of them were initially negative value which were indicating return
4) Handling Outlier / Missing values - The interquartile range method was used to remove any outliers to produce better data
   ![image](https://github.com/user-attachments/assets/4a762082-f636-4316-82d0-e5c73319dd9c)
  ![image](https://github.com/user-attachments/assets/a6062f1f-02d3-4a73-bed9-fa47778b0d66)
5) Attribute Transformation - Date of birth were converted into age and date of purchase were converted into month of purchase to ease the analysis along the way
6) Feature Selectiom - Attribute which contribute least information for the analysis is removed

Exploratory Data Analysis (EDA
1) Normality Check - Shapiro-Wilk Test is used to check the normality
![image](https://github.com/user-attachments/assets/ce2bd043-c50e-487f-b425-91fa6a01b52f)
p-value obtained was 0.0000 thus rejecting H_0 indicating the data is nor normally distributed. The issue of p-value almost close to 0 is because the observation size is large. To confirm the inference, Anderson-Darling test is done.
