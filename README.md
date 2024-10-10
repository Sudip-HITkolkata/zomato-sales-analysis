# Zomato_sales_analysis

In this project, Zomato's customer data was analyzed to gain insights into customer preferences, restaurant types, and order trends. The analysis aimed to help Zomato optimize its operations and improve customer satisfaction by targeting specific areas such as restaurant types, customer preferences, and order modes. The project covers the following key areas:

## Key Features

- **Popular Restaurant Types:**
Objective: Identify the type of restaurants (e.g., cafes, fast food, fine dining) from which the majority of customers order.
Method: Analyze the frequency of orders from each restaurant type using Pandas for data manipulation and visualization libraries like Matplotlib or Seaborn for presenting insights.

- **Customer Votes per Restaurant Type:**
Objective: Calculate the total number of votes each type of restaurant has received from customers.
Method: Group the dataset by restaurant type and sum up the customer votes, visualizing the results to understand customer preferences.

- **Majority Restaurant Ratings:**
Objective: Determine the common rating range (e.g., 3-4 stars, 4-5 stars) that the majority of restaurants have received.
Method: Use statistical functions and visualizations to analyze the distribution of ratings and identify the most frequent rating range.

- **Average Spending by Couples:**
Objective: Since couples are observed to order more online, calculate their average spending per order.
Method: Filter orders by "couple" and calculate the average order value using aggregation techniques in Pandas.

- **Comparison of Ratings by Mode (Online vs. Offline):**
Objective: Find out which mode (online or offline) has received the highest average rating.
Method: Separate data by order mode and calculate average ratings for both online and offline orders to compare them.

- **Restaurants with More Offline Orders:**
Objective: Identify the type of restaurant that receives more offline orders so Zomato can offer targeted discounts.
Method: Analyze the data for offline orders and identify which restaurant types are preferred for offline dining. Use this insight for Zomato's marketing strategy.

## Technologies Used

- **Pandas:** For data cleaning, manipulation, and aggregation.
- **Matplotlib/Seaborn:** For data visualization.
- **NumPy:** For numerical operations.
- **Jupyter Notebook:** For interactive analysis and visualization.


