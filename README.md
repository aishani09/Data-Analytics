# Zomato-Analysis
 This project provides an insightful analysis of restaurant data sourced from Zomato. The analysis focuses on key metrics such as restaurant ratings, price ranges, cuisines, and locations, allowing users to filter data by city and extract valuable insights.
# Overview
 The main objective of this project is to analyze restaurant data to uncover trends, identify top-performing restaurants, and understand customer preferences across various cities. Interactive visualizations are created using Python libraries such as Plotly and Seaborn, offering an intuitive way to explore the data.

# Features
1. Top 10 Restaurants by City: Users can filter restaurants by city and view the top 10 based on ratings and votes.
2. Rating Distribution: Visualizes restaurant ratings in different categories like Excellent, Very Good, Good, Average, and Poor.
3. Cuisine and Price Analysis: Provides insights into the distribution of cuisines and their corresponding price ranges across various cities.
4. Interactive Dashboard: Allows for real-time filtering based on user input (city selection) and provides dynamic visualizations.
5. Location-Based Insights: Analyzes the influence of location on restaurant performance, price, and popularity.
   
# Visualizations
1. Top 10 Restaurants: A bar chart of the top 10 restaurants in a selected city, sorted by ratings or votes.
2. Rating Distribution: A pie chart or bar plot showing the distribution of ratings (Excellent, Good, Average, Poor, etc.).
3. Price vs. Votes: A scatter plot visualizing the relationship between restaurant prices and customer votes.
4. Cuisine Popularity: A bar plot displaying the most popular cuisines across various locations.
5. Location Analysis: Heatmap visualizing the concentration of restaurants by city or region.
   
# Technologies Used
1. Python: For data analysis and manipulation.
2. Pandas: For data cleaning, filtering, and aggregation.
3. Matplotlib: For additional static visualizations.
4. Jupyter Notebook: For organizing and running the analysis in a readable format.

   

### Dataset - https://www.kaggle.com/datasets/shrutimehta/zomato-restaurants-data
### Dataset Description - 
The collected data has been stored in the Comma Separated Value file Zomato.csv. Each restaurant in the dataset is uniquely identified by its Restaurant Id. Every Restaurant contains the following variables:

1. Restaurant Id: Unique id of every restaurant across various cities of the world
2. Restaurant Name: Name of the restaurant
3. Country Code: Country in which restaurant is located
4. City: City in which restaurant is located
5. Address: Address of the restaurant
6. Locality: Location in the city
7. Locality Verbose: Detailed description of the locality
8. Longitude: Longitude coordinate of the restaurant's location
9. Latitude: Latitude coordinate of the restaurant's location
10. Cuisines: Cuisines offered by the restaurant
11. Average Cost for two: Cost for two people in different currencies 👫
12. Currency: Currency of the country
13. Has Table booking: yes/no
14. Has Online delivery: yes/ no
15. Is delivering: yes/ no
16. Switch to order menu: yes/no
17. Price range: range of price of food
18. Aggregate Rating: Average rating out of 5
19. Rating color: depending upon the average rating color
20. Rating text: text on the basis of rating of rating
21. Votes: Number of ratings casted by people


