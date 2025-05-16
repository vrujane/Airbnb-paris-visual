# 🌟 Paris Airbnb Listings - Data Visualization Project

📌 Project Overview

This project analyzes and visualizes Airbnb listings in Paris to uncover trends in pricing, availability, neighborhood popularity, and property types. The goal is to provide insights for travelers, hosts, and real estate analysts using interactive visualizations powered by Python (Pandas, Matplotlib, Seaborn, Plotly)

📂 Dataset

The dataset used is "Paris Airbnb Listings" from [Inside Airbnb](http://insideairbnb.com/get-the-data/)

📊 Key Visualizations

# Task 1: Interactive Map of Available Housing
**Description:**
Create an interactive map of the selected city displaying Airbnb listings. Use different colors or marker sizes based on price. Add pop-up windows showing the property name and price.

**What to analyze:**
In which neighborhoods is the most housing available?
Which neighborhoods offer the most expensive/cheapest listings?

### Top 5 Neighborhoods with the Most Available Listings

| Rank | Neighbourhood        | Total Listings | Average Price (€) |
|------|----------------------|----------------|-------------------|
| 1    | Buttes-Montmartre    | 10,532         | 178.99            |
| 2    | Popincourt           | 8,392          | 210.76            |
| 3    | Vaugirard            | 7,727          | 245.56            |
| 4    | Batignolles-Monceau  | 6,673          | 265.82            |
| 5    | Entrepôt             | 6,464          | 217.84            |

### Top 5 Most Expensive Neighborhoods

| Rank | Neighbourhood    | Total Listings | Average Price (€) |
|------|------------------|----------------|-------------------|
| 1    | Élysée           | 2,965          | 442.04            |
| 2    | Palais-Bourbon   | 2,702          | 409.84            |
| 3    | Passy            | 6,225          | 407.62            |
| 4    | Louvre           | 2,042          | 338.56            |
| 5    | Luxembourg       | 2,724          | 336.12            |

### Top 5 Cheapest Neighborhoods

| Rank | Neighbourhood    | Total Listings | Average Price (€) |
|------|------------------|----------------|-------------------|
| 1    | Ménilmontant     | 5,183          | 160.13            |
| 2    | Buttes-Montmartre| 10,532         | 178.99            |
| 3    | Gobelins         | 3,274          | 181.35            |
| 4    | Buttes-Chaumont  | 5,387          | 189.86            |
| 5    | Observatoire     | 3,603          | 202.41            |


![alt text](task1.png)

![alt text](task1-2.png)
# Task 2: Histogram of Price Distribution
**Description:**
Build a histogram showing the distribution of prices per night. Use a logarithmic scale if there are outliers with extremely high prices in the data.

**What to analyze:**
What price range occurs most frequently?
Are there any outliers (extremely high or low prices)?
Which neighborhoods offer more budget-friendly housing?

![alt text](image.png)

# Task 3: Review and Rating Analysis by Neighborhood
**Description:**
Calculate the average rating and the number of reviews for each neighborhood. Create a horizontal bar chart to show which neighborhoods have the highest ratings.

**What to analyze:**
Which neighborhoods receive the best reviews?
Is there a connection between price and rating?
Which neighborhoods might be attractive for rental based on reviews?
### Neighborhoods by Average Reviews per Month

| Rank | Neighbourhood     | Avg Reviews/Month | Total Count |
|------|-------------------|-------------------|-------------|
| 1    | Bourse            | 1.55              | 2,473       |
| 2    | Louvre            | 1.39              | 1,580       |
| 3    | Élysée            | 1.29              | 2,020       |
| 4    | Temple            | 1.24              | 3,114       |
| 5    | Palais-Bourbon    | 1.22              | 1,902       |
| 6    | Hôtel-de-Ville    | 1.21              | 2,214       |
| 7    | Vaugirard         | 1.18              | 5,464       |
| 8    | Opéra             | 1.17              | 3,396       |
| 9    | Entrepôt          | 1.15              | 4,958       |
| 10   | Reuilly           | 1.13              | 2,758       |
| 11   | Luxembourg        | 1.11              | 1,986       |
| 12   | Panthéon          | 1.11              | 2,335       |
| 13   | Passy             | 1.08              | 3,715       |
| 14   | Observatoire      | 1.03              | 2,540       |
| 15   | Gobelins          | 1.03              | 2,305       |


![qw](image-1.png)

# Task 4: Correlation Between Price and Property Type
**Description:**
Calculate the average price for each property type (e.g., "Private Room," "Entire Apartment"). Visualize this using a bar chart.

**What to analyze:**
Which property type is the most expensive/cheapest?
Is there a price difference for the same property type in different neighborhoods?
How does the property type affect popularity (e.g., by the number of reviews)?

![rt](image-2.png)

![alt text](image-3.png)

![alt text](image-4.png)

# Task 5: Heatmap of Property Density
**Description:**
Create a heatmap showing where Airbnb properties are most concentrated in the city.

**What to analyze:**
Which neighborhoods have the highest concentration of listings?
Is there a connection between property concentration and price?
Does proximity to popular tourist attractions affect property density?




### Neighborhoods by Listing Count and Average Price

| Rank | Neighbourhood        | Listings Count | Average Price (€) |
|------|----------------------|----------------|-------------------|
| 1    | Buttes-Montmartre    | 10,532         | 178.99            |
| 2    | Popincourt           | 8,392          | 210.76            |
| 3    | Vaugirard            | 7,727          | 245.56            |
| 4    | Batignolles-Monceau  | 6,673          | 265.82            |
| 5    | Entrepôt             | 6,464          | 217.84            |
| 6    | Passy                | 6,225          | 407.62            |
| 7    | Buttes-Chaumont      | 5,387          | 189.86            |
| 8    | Ménilmontant         | 5,183          | 160.13            |
| 9    | Opéra                | 4,652          | 257.74            |
| 10   | Reuilly              | 3,988          | 216.95            |

![alt text](image-5.png)

![alt text](task5.png)
## 🔍 Key Insights
- Buttes-Montmartre has the highest number of listings (10,532) with relatively affordable prices (€178.99 avg)
- Élysée district commands premium prices (€442.04 avg) despite fewer listings
- Ménilmontant offers the most budget-friendly options (€160.13 avg)
- Bourse neighborhood generates the most reviews per month (1.55)















