# Data Analysis and Visualization using Google BigQuery, Pandas, Numpy, Matplotlib, Seaborn, Plotly of Google Merchandise Store
Using a sample data set that contains Google Analytics 360 data from the Google Merchandise Store, I used Python and Google BigQuery to explore 3 months of the site's performance in 2016. I visualized and examined patterns using Python libraries and using Google BigQuery to export table data based on different criterias.

To view notebook/kernel in Kaggle platform, click [here](https://www.kaggle.com/linayang/google-analytics-sample-eda). 

# Google Merchandise Store and Google Analytics
Google Analytics allows e-commerce and website administrators understand the efficacy of campaigns and offers insight into an online business. In this exploratory data analysis, the analysis takes a look at the Google Merchandise Store and how it performed during the fourth quarter in 2016 (October-December). 

# Data Visualization Samples
### Abandoned cart funnel visualization
Funnel visualizations are helpful in tracking shopping cart abandonment. We can see that we had a conversion rate of 18% and an overall abandoned cart rate of 82% during this quarter and the biggest drop off point is during the checkout process. 

![abandoned cart funnel](https://github.com/linayang-io/python-ga-eda-worksample/blob/master/lyang_funnel_viz_demo.gif)
### Box plot of product price offerings
This box plot shows the distribution of product prices on the Google Merchandise Store by product category. It shows outliers in pricing by product category as well as the median average price of each product offering. 

![box whisker plot](https://github.com/linayang-io/python-ga-eda-worksample/blob/master/lyang_boxwhisker_eda_sample.png)
# Insights and Conclusion
Based on the [exploratory data analysis](https://github.com/linayang-io/python-ga-eda-worksample/blob/master/google-analytics-sample-eda.ipynb) the Google Merchandise Store had over 3,000 visits, almost 93,000 pageviews and earned $386,200 in revenue in 2016Q4. Referral traffic has generated the most revenue as well as garnered the most users to the Google Merchandise store. December generated over $153,000 in revenue and garnered almost 1,400 visits to the Google Merchandise store. The revenue generated in December accounted for 40% of Q4 sales, indicating a holiday surge that is typically seen in retail. Interestingly, while Direct traffic has generated more revenue than Organic Search, Organic Search has led to more transactions and users during this fiscal quarter. While Apparel generated the most revenue during Q4, Office Supplies were sold the most. There was an abandoned cart rate of 82% which is slightly above average for e-commerce. We see the biggest drop off is during the checkout process. It may be beneficial to set up a triggered abandoned cart email at this point of sale to lead to more conversions. 
