# Zomato Restaurants Analysis

Welcome to the Zomato Restaurants Analysis repository! This project involves analyzing restaurant data from Zomato to derive meaningful insights and trends.

## Data

The dataset used in this project includes information such as:
- **Restaurant ID**: Unique identifier for each restaurant.
- **Restaurant Name**: Name of the restaurant.
- **Country Code**: Code representing the country where the restaurant is located.
- **City**: City where the restaurant is located.
- **Address**: Street address of the restaurant.
- **Locality**: Locality (neighborhood) of the restaurant.
- **Locality Verbose**: Detailed locality description.
- **Longitude**: Longitude coordinate of the restaurant's location.
- **Latitude**: Latitude coordinate of the restaurant's location.
- **Cuisines**: Types of cuisines offered by the restaurant.
- **Average Cost for two**: Average cost for two people dining at the restaurant.
- **Currency**: Currency used for pricing.
- **Has Table booking**: Whether the restaurant allows table booking (yes/no).
- **Has Online delivery**: Whether the restaurant offers online delivery (yes/no).
- **Is delivering now**: Whether the restaurant is currently delivering (yes/no).
- **Switch to order menu**: Option to switch to ordering menu (yes/no).
- **Price range**: Price range of the restaurant (1 to 4, with 1 being lowest and 4 being highest).
- **Aggregate rating**: Average rating given by users.
- **Rating color**: Color corresponding to the aggregate rating.
- **Rating text**: Text representation of the aggregate rating (e.g., Excellent, Good).
- **Votes**: Number of votes/ratings received from users.

### Data Source

The data is obtained from Zomato's API and publicly available datasets. Ensure you comply with Zomato's terms of use when using this data.

### Data Files

- `zomato.csv`: The main dataset containing restaurant details.
- `Country-Code.csv`: Has columns [Code ,Country].

# Zomato Restaurants Analysis

## Country Density

![Country Density](plot_country_density.png)

- The histogram shows the density of restaurants across different countries, with a logarithmic scale on the y-axis.

## Average Cost for Two

![Average Cost for Two](plot_avg_cost.png)

- Bar plot displaying the average cost for two people dining at restaurants in different countries, with a logarithmic scale on the y-axis.

## Average Price Range

![Average Price Range](plot_avg_price_range.png)

- Bar plot depicting the average price range of restaurants in different countries, with a logarithmic scale on the y-axis.

## Average Votes

![Average Votes](plot_avg_votes.png)

- Bar plot showing the average number of votes received by restaurants in different countries, with a logarithmic scale on the y-axis.

## Restaurant Count by Country and Aggregate Rating

![Restaurant Count by Country and Aggregate Rating](plot_restaurant_count_rating.png)

- Bar plot illustrating the count of restaurants by country and their aggregate rating, with a logarithmic scale on the x-axis.

## Restaurant Count by Country and Rating Text

![Restaurant Count by Country and Rating Text](plot_restaurant_count_rating_text.png)

- Histogram showcasing the count of restaurants by country and their rating text, with a logarithmic scale on the y-axis.

## Percent of Restaurant Count by Country and Rating

![Percent of Restaurant Count by Country and Rating](plot_percent_rating.png)

- Bar plot displaying the percentage of restaurant counts by country and their rating, calculated as a percentage of the total restaurant count per country.

## Restaurant Votes by Country and Rating Text

![Restaurant Votes by Country and Rating Text](plot_votes_rating.png)

- Bar plot illustrating the percentage of restaurant votes by country and their rating text, calculated as a percentage of the total votes per country.

## Rating Color Density

![Rating Color Density](plot_rating_color.png)

- Histogram displaying the density of rating colors assigned to restaurants across different countries, with a logarithmic scale on the y-axis.

## Restaurant Percentages by Country and Rating Color

![Restaurant Percentages by Country and Rating Color](plot_percent_rating_color.png)

- Bar plot showing the percentages of restaurants by country and their rating color, calculated as a percentage of the total restaurant count per country.

## Restaurant Votes by Country and Rating Color

![Restaurant Votes by Country and Rating Color](plot_votes_rating_color.png)

- Bar plot illustrating the percentages of restaurant votes by country and their rating color, calculated as a percentage of the total votes per country.

## Has Table Booking

![Has Table Booking](plot_has_table_booking.png)

- Histogram showing the density of restaurants with and without table booking options across different countries, with a logarithmic scale on the y-axis.

## Has Online Delivery

![Has Online Delivery](plot_has_online_delivery.png)

- Histogram depicting the density of restaurants with and without online delivery options across different countries, with a logarithmic scale on the y-axis.

## Top 10 Cuisines Density

![Top 10 Cuisines Density](plot_top_10_cuisines.png)

- Bar plot displaying the density of the top 10 most offered cuisines in restaurants across different countries, with a logarithmic scale on the y-axis.

## Top 10 Cuisines Density upon Restaurant per Country

![Top 10 Cuisines Density upon Restaurant per Country](plot_top_10_cuisines_country.png)

- Bar plot showing the density of the top 10 most offered cuisines in restaurants, specifically across different countries, calculated as a percentage of the total restaurant count per country.

## Top 5 Cuisines Density in Each Country

- The analysis below shows the top 5 cuisines by density in each country:

![Top 5 Cuisines Density in Each Country](Top 5 Cuisines Density in each Country.png)

- This set of pie charts displays the density of the top 5 most offered cuisines in restaurants across different countries. Each chart represents a specific country, illustrating the percentage distribution of these cuisines.

## Top 5 Foods Density in Different Ratings

![Top 5 Foods Density in Different Ratings](plot_top_5_foods_ratings.png)

- The analysis is divided into three parts (Excellent, Good, and Average), each displaying the top 5 cuisines by density across different countries and rating categories.


