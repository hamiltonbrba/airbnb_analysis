
# Analyzing Seasonal Trends and Their Impact on Airbnb Prices

### Executive Summary
This project analyzes the impact of seasonal trends on Airbnb listings, focusing on metrics such as price, number of reviews, reviews per month, and availability. Our analysis reveals significant seasonal variations in these metrics, which have important implications for both Airbnb hosts and guests. Notably, prices peak in Late Summer, while guest activity is highest in Late Summer and Early Fall. The findings suggest optimal times for pricing adjustments and booking strategies.

### Team Members
Bryan, Nebiat, Jazmin

### Project Description/Outline
This project aims to analyze how seasonal trends affect various metrics of Airbnb listings, such as price, number of reviews, reviews per month, and availability. By leveraging the data, we can find insights into seasonal variations and their correlation with Airbnb pricing. The project focuses on identifying patterns and trends that can inform hosts and potential guests about the best times to rent or stay at an accommodation property.

### Research Questions
1. How do average nightly rental prices for Airbnb properties vary by season?
2. How do the number of reviews, reviews per month, and availability change with the seasons?
3. What is the correlation between average nightly rental prices and other metrics (number of reviews, reviews per month, availability) across different seasons?

### Major Findings and Implications
**1. Number of Reviews and Price by Detailed Season**

- **Observation**: The number of reviews peaks in Late Summer, corresponding with the highest prices during this period. This suggests that guest activity is closely tied to peak pricing seasons.
  
  - **Implications for Hosts**: Encouraging reviews during peak seasons can boost property visibility and attract more guests. 
  - **Implications for Guests**: Consider booking during off-peak seasons when prices are lower and competition for listings is reduced.

![Average Number of Reviews and Price by Detailed Season](Images/Average%20Number%20of%20Reviews%20&%20Price%20by%20Detailed%20Season.png)

**2. Reviews per Month and Price by Detailed Season**

- **Observation**: Reviews per month peak in Early Fall, with prices peaking in Late Summer. This indicates that guest feedback is higher during Early Fall, possibly due to the high guest activity in the preceding Late Summer.

  - **Implications for Hosts**: Hosts can use the feedback from Early Fall to enhance their services and attract more guests in subsequent seasons.
  - **Implications for Guests**: Increased reviews in Early Fall provide more insight into the quality of listings during this time.

![Average Reviews per Month and Price by Detailed Season](Images/Average%20Reviews%20per%20Month%20&%20Price%20by%20Detailed%20Season.png)

**3. Box and Whiskers Plot of Average Prices by Season**

- **Observation**: Prices are most variable in the summer months, indicating that this is the peak season with a wide range of listing prices. Winter months show the least variability, reflecting lower and more consistent pricing.

  - **Implications for Hosts**: Understanding the variability in summer pricing can help in setting competitive rates.
  - **Implications for Guests**: Guests should be cautious of price surges in the summer and consider booking early to secure better deals.

![Box and Whiskers Plot of Average Prices by Season](Images/box%20plot%20of%20average%20prices%20by%20season.png)

**4. Histogram of Average Prices**

- **Observation**: The histogram shows a fairly normal distribution of prices across seasons, with most listings priced between $100 and $200 per night. Summer months, however, show a higher frequency of listings in the upper price range.

  - **Implications**: The distribution supports the idea that summer is a peak season with higher demand and pricing.

![Histogram of Average Prices](Images/Histogram%20of%20Average%20Prices.png)

**5. Scatter Plot of Price vs. Number of Reviews by Season**

- **Observation**: There is no significant correlation between the number of reviews and the price, as shown by the scatter plot and the flat regression line.

  - **Implications for Hosts and Guests**: This indicates that price alone does not drive the number of reviews, suggesting other factors like location, amenities, and service quality may be more influential.

![Scatter Plot of Price vs. Number of Reviews by Season](Images/Scatterplot%20Price%20vs%20number%20of%20reviews.png)

### ANOVA Test Results
**Statistical Analysis**:
- **Price**: F-value = 42.14, P-value = 5.22e-59. This is statistically significant for price.
- **Number of Reviews**: F-value = 22.15, P-value = 5.99e-30. This is statistically significant for number of reviews.
- **Reviews per Month**: F-value = 78.04, P-value = 7.71e-111. This is statistically significant for reviews per month.
- **Availability**: F-value = 24.05, P-value = 1.07e-32. This is statistically significant for availability.

**Conclusion**: All p-values are significantly below 0.05, confirming significant seasonal variations in Airbnb metrics. These findings support the hypothesis that seasonal trends impact key Airbnb metrics, particularly pricing and guest activity.

### Recommendations
- **For Hosts**: Adjust prices and manage availability seasonally, and encourage reviews year-round to optimize visibility and revenue.
- **For Guests**: Book during off-peak seasons for better deals and availability, and leave reviews to contribute to host and guest community knowledge.

### Data Processing and Filtering
Due to significant outliers in the dataset (e.g., properties with prices up to $12,000 per night), we limited the dataset to prices of $350 and below to focus on more affordable and typical Airbnb listings.

### Limitations with Data Manipulation
- **Date Issues**: The only dates available were for the last review, limiting the ability to analyze stays across an entire year.
- **Price Outliers**: The vast range of prices necessitated limiting the analysis to properties priced $350 or below per night for better data relevance.

---

**Key Improvements Based on Feedback**:
1. **Contextualized Visualizations**: Each chart is introduced with context, and its relevance to the overall analysis is clearly explained.
2. **Executive Summary**: A summary at the top provides a quick overview of the findings for those who may not want to delve into the details.
3. **Clearer Narratives**: The story is structured to flow logically from the research questions to the findings, statistical analysis, and conclusions, with fewer, more impactful charts. 

