# :oncoming_automobile:  Exploratory Data Analysis on USA Car Accidents  

**Are Car Accidents More Likely to Occur during the Winters?**

In this Project, I have performed Exploratory Data Analysis on a dataset regarding Car Accidents in USA. The dataset contains records of 6 years from Feb 2016 to Dec 2021 and contains 2.8 million records in total.

The project aims at finding trends, patterns and anomalies in the dataset. Python Libraries like Numpy, Pandas, Matplotlib, Seaborn and Folium have been used for the same. 

The hypothesis in the question above has also been tested by slicing and dicing the data for every year. Following are the insights and findings of the project.

*Walk through the **Jupyter Notebook [here](https://github.com/PriyaPalak/EDA-on-US-Accidents-using-Python/blob/main/US%20Car%20Accidents%20Jupyter%20Notebook.ipynb)** to understand the approach more comprehensively.*

## :memo: Insights & Findings

1. The dataset covers 49 states and more than 11000 cities of USA. `Miami` is the city with the maximum number of accidents. New York and Chicago are the two most populated cities, but still they do not appear in the list of top 20 Cities with maximum number of accidents.

2. `34` cities have witnessed more than 10,000 accidents over the 6 years. `4%` of the Cities have accidents between 1000 and 10,000. Around `2000` cities have reported 1 or 2 accidents over past 5 years, which is quite unbelievable.
Less and less cities have high number of accidents. In fact, the number of accidents per city seems to decrease exponentially.

3. Morning(`8 AM to 9 AM`) and Evening(`3 PM to 7 PM`) rush hours witness the highest number of accidents in a day. Weekdays account for higher number of accidents compared to Weekends in a week. The trend of accidents by hour follows the same pattern on Mondays as on all days of the week combined. However, on weekends, the distribution is more spread out.

4. The distribution of accidents is quite balanced over the months for the years 2016, 2017 and 2018. However, for the years 2019, 2020 and 2021 , the summer months account for lower number of accidents comparatively. The pace picks up from September-October and peaks around December.

     Over the 6 years, we see an `increasing trend` in the number of accidents.

5. Most of the accidents have occurred on or near the `coastal areas`.  
`89%` of the accidents had severity of `2` which means moderate impact on traffic. And `4.61% `of the accidents had a huge impact on the traffic eith a severity of `4`. On an average, the severity of an accident was `2.138`.

