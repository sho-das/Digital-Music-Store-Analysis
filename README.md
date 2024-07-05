# Digital Music Store Analysis

## Project Overview

This project analyzes music store data to answer a series of questions using PostgreSQL. The analysis covers various aspects of the store's operations, including employee hierarchy, sales distribution, customer behavior, and music preferences.

## Objectives

1. Employee Analysis:
 - Identify the senior-most employee based on job title.
 - Sales Distribution:

2. Determine which countries have the most invoices.
 - Identify the top three invoice values.
 - Find the city with the highest sum of invoice totals to plan a promotional event.

3. Customer Insights:
 - Recognize the best customer by the total money spent.

4. Music Preferences:
 - List Rock music listeners with their email, first name, last name, and genre.
 - Invite the top 10 rock bands by track count.
 - List all tracks longer than the average song length, ordered by length.

5. Advanced Analysis:
 - Calculate the amount spent by each customer on different artists.
 - Determine the most popular music genre in each country based on purchases.
 - Identify the top spending customer in each country.

## Outcomes:

This project provides insights into:

1. Employee Hierarchy:
 - Understand the organizational structure and identify key personnel.

2. Sales Trends:
 - Recognize high-performing countries and cities to focus marketing efforts.
 - Identify the highest value invoices to understand significant sales.

3. Customer Behavior:
 - Determine the best customers to tailor loyalty programs.
 - Understand customer preferences in music genres and artists.

4. Music Analysis:
 - Identify popular music tracks and genres for targeted promotions.
 - Recognize top rock bands for potential collaborations.

5. Data-Driven Decisions:
 - Enable better planning for promotional events based on sales data.
 - Inform strategies for customer retention and engagement through detailed spending analysis.

## Database and Tools
* Postgre SQL
* PgAdmin4

## Schema- Music Store Database  
![MusicDatabaseSchema](https://user-images.githubusercontent.com/112153548/213707717-bfc9f479-52d9-407b-99e1-e94db7ae10a3.png)
- **Employees**: Information about the store's employees
- **Customer**: Details about the customers
- **Invoice**: Sales transaction records
- **Playlist**: Information about user-created playlists
- **Playlist_Track**: Association between playlists and tracks
- **Artist**: Details about the artists
- **Album**: Information about the albums
- **Track**: Details about the individual tracks
- **Media Types**: Types of media formats
- **Genre**: Music genres

## Insights
- 📋 Most Senior Employee: Madan Mohan
- 🎸 Best Selling Artist: Queen
- 🎵 Most Favorite Genre: ROCK
- 💵 Best Customer: R Madhav
- 🏆 Top Spending Customer for Best Selling Artist: Hugh O’Reilly
- 🏴 Top Country by Invoices: USA
- 🌆 Top City by Total Amount: PRAQUE, 273.24

## Key Functions Used:
SELECT, Aggregates, GROUP BY,ORDER BY JOINs,LIMIT,Window functions, CTE,Sub-Query, Advanced JOINs.
