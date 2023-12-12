# Final-Project-Statistical-Modelling-with-Python
## Project/Goals
  The project aims to explore and analyze two distinct APIs, Yelp and Foursquare, alongside statistical modeling techniques to derive insights into bike stations and     
  restaurant ratings within a specific geographic location. The primary objectives included:
- Assessing and comparing API coverage and data quality between Yelp and Foursquare.
- Understanding the relationship between restaurant ratings and the availability of free bikes at bike stations.
- Developing a statistical model to predict free bike availability based on ratings and bike station counts.

## Process

### 1.  Data Exploration and API Analysis
- Explored the structure and data from both Yelp and Foursquare APIs.
- Conducted an analysis of the retrieved data to understand the available information on bike stations and restaurant ratings.
   
### 2. Data Validation and Preparation
- Checked for missing or inconsistent data within each dataset.
- Inspected the structure, columns, and data types of the Yelp dataset (new_yelp_df1) using queries and visualization tools.

### 3. Statistical Modelling
1. Analyzed correlations between variables like 'rating', 'distance', and 'free_bikes'.
2. Investigated the influence of restaurant ratings on the availability of free bikes using regression analysis.
3. Performed OLS regression to predict free bike availability based on 'rating' and 'bike_station', eliminating insignificant variables.

 ## Results

### API Comparison
The Yelp API provided more comprehensive data, including detailed information such as restaurant name, image URL, status (open/closed), reviews, categories, ratings, and location specifics. This emphasis on user-generated reviews contributed to a richer and more accurate representation of restaurant quality and popularity compared to Foursquare.

### Statistical Model Insights
- Found a moderate positive correlation between the number of free bikes and restaurant ratings, indicating a slight tendency for higher-rated restaurants to have more available free bikes.
- Developed an OLS regression model predicting free bike availability based on 'rating' and 'bike_station'.
  - The model explained approximately 30.2% of the variability in free bike availability.
  - 'bike_station' showed a significant negative relationship with 'free_bikes', while 'rating' exhibited a marginal positive relationship.

## Challenges 

Challenges faced during the project:

- Handling missing or inconsistent data within API responses.
- Joining and merging the data based on common columns
- Addressing potential multicollinearity issues in the regression model.
- Interpreting nuanced relationships between variables due to weak correlations.


## Future Goals
Given more time, potential future goals for this project are:
- Exploring additional variables or datasets to enhance the strength of the model.
- Conducting thoughtful analysis on user reviews to further understand their impact on bike station dynamics.
- Implementing more variables such as distance and location into the model to see if they're factors

