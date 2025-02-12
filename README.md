The retail industry is evolving rapidly, with competition driving the need for data-driven decision-making. Leveraging data analytics allows retailers to gain valuable insights into customer behavior, product performance, and transaction trends, ena-bling them to enhance customer satisfaction and drive profitability. Retailers increas-ingly rely on customer intelligence to predict future behaviors, optimize inventory, and design personalized marketing strategies.

The objective of the assignment are as follows;
1)	To employ data cleaning techniques for improved retail data quality
2)	To visualize the pre-processed data and identify patterns between attributes

**Data Cleaning**
1) Missing Values - Missing values has been screened and they have been replaced with the mode since the they were categorical data
2) Negative Values - There could be no negative value on the total amount and they were converted into positives. Negative values indicated items being returned
3) Duplicated rows - Both the duplicated rows were deleted as one of them were initially negative value which were indicating return
4) Handling Outlier / Missing values - The interquartile range method was used to remove any outliers to produce better data
   ![image](https://github.com/user-attachments/assets/4a762082-f636-4316-82d0-e5c73319dd9c)
  ![image](https://github.com/user-attachments/assets/a6062f1f-02d3-4a73-bed9-fa47778b0d66)
5) Attribute Transformation - Date of birth were converted into age and date of purchase were converted into month of purchase to ease the analysis along the way
6) Feature Selectiom - Attribute which contribute least information for the analysis is removed

**Exploratory Data Analysis (EDA)**
1) Normality Check - Shapiro-Wilk Test is used to check the normality

![image](https://github.com/user-attachments/assets/ce2bd043-c50e-487f-b425-91fa6a01b52f)

p-value obtained was 0.0000 thus rejecting H_0 indicating the data is nor normally distributed. The issue of p-value almost close to 0 is because the observation size is large

The distribution graph of the Total Amount also shows that the data is skewed to the right. This confirms visually that the data does not follow the normal distribution.

![image](https://github.com/user-attachments/assets/764b00f2-5b1a-4ff5-9dcb-b6fb1a8650e0)

2) Correlation between attributes
The correlation coefficient between the attributes is calculated in order to identify the strength of correlation between the attributes.

![image](https://github.com/user-attachments/assets/9e2d08a7-180b-469e-986e-3aae53ecb161)

There is strong correlation between tax of the item and total amount purchase. Apart from that, rate and total amount and finally rate and tax also having strong correlation between them.

3)Descriptive Statistics
Statistics are calculated for the numerical attributes

![image](https://github.com/user-attachments/assets/503b1db0-74e8-4829-8f85-1307d5f546fa)

4) Visualisation of non numerical attributes
Stacked bar graph of Gender, shop type against Frequency

![image](https://github.com/user-attachments/assets/3fd16b9e-ed2d-4b2a-8fb9-3d4e5307d645)

Distribution Graph of Month against frequency

![image](https://github.com/user-attachments/assets/4fc63530-c35d-412c-997a-8a02f713137a)

Pie graph of store type against frequency

![image](https://github.com/user-attachments/assets/d8f1650a-1ab9-4bb6-a878-3d6ba9e4b494)

Bar Graph of Gender, Category against Frequency

![image](https://github.com/user-attachments/assets/a5f1ae21-8aa0-42b5-b4bd-18e673842e77)

Transaction Trends across store type over time

![image](https://github.com/user-attachments/assets/85d780cb-f153-4e66-8427-402f4beec263)


**Conclusion**

The e-Shop consistently has the highest transaction count, remaining above 200, while Flagship stores, MBR, and TeleShop have lower, fluctuating trends around 100–150. A sharp increase is observed in early 2011, followed by relatively stable trends. The e-Shop exhibits noticeable periodic fluctuations, peaking regularly, while other store types show more gradual variations. Towards early 2014, all store types experience a decline in transactions. Overall, the data suggests that online stores (e-Shop) dominate in transaction volume, while physical stores show more variability and moderate growth.

The retailers can look into improvement of the e-Shop which would be beneficial in the future. Apart from tha, retailers might need to do more promotions and advertising on the physical stores. On the products, retailers are having good sales of books, electronics and home and kitchen products. These items needs to be stored efficiently in the store so that it meet the demands from the customer.


