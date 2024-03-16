# Aerofit Treadmill Customer Analysis

## Problem Statement

Aerofit, a leading fitness equipment brand, aims to identify the characteristics of the target audience for each type of treadmill it offers. The company wants to provide better recommendations to new customers by understanding the differences in customer characteristics across its product range.

## Dataset

The dataset contains information on individuals who purchased a treadmill from Aerofit stores over the prior three months. The features include:

- Product Purchased: KP281, KP481, or KP781
- Age: In years
- Gender: Male/Female
- Education: In years
- Marital Status: Single or partnered
- Usage: Average weekly usage of the treadmill
- Income: Annual income (in $)
- Fitness: Self-rated fitness level on a scale of 1 to 5
- Miles: Average weekly distance expected to walk/run

## Data Analysis Steps

1. **Import and Preliminary Analysis**: 
   - Import the dataset and perform basic data analysis steps like checking the structure and characteristics of the dataset.
   
2. **Outlier Detection**: 
   - Use boxplots and statistical methods to detect outliers, if any, in the dataset.
   
3. **Effect of Features on Product Purchased**:
   - Explore how features like marital status, age, etc., affect the choice of treadmill product using visualizations such as countplots, histplots, and boxplots.
   
4. **Marginal Probability Analysis**: 
   - Calculate the marginal probability of each treadmill product purchased by customers using pandas.crosstab.
   
5. **Correlation Analysis**: 
   - Check the correlation among different factors using heatmaps or pair plots to understand relationships between variables.
   
6. **Customer Profiling**: 
   - Categorize users based on their characteristics and purchasing behavior.
   
7. **Probability Analysis**: 
   - Calculate marginal and conditional probabilities to understand customer preferences and behaviors.
   
8. **Business Insights**:
   - Provide insights on the range and distribution of attributes, as well as relationships between variables.
   - Offer actionable recommendations for the business based on the analysis.

## Recommendations

1. **Targeted Marketing**: Tailor marketing efforts based on customer profiles identified through analysis.
2. **Product Development**: Use insights to improve existing products or develop new ones catering to specific customer segments.
3. **Customer Engagement**: Engage with customers through personalized recommendations and offerings.
4. **Sales Strategy**: Adjust pricing or promotional strategies based on customer preferences and purchasing patterns.
5. **Customer Service**: Enhance customer service by addressing concerns or needs identified through analysis.

The analysis aims to provide actionable insights to Aerofit for better understanding and catering to its customer base effectively.
