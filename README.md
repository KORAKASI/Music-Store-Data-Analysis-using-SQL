# Music-Store-Data-Analysis-using-SQL
This project analyzes a Music Store relational database using SQL to extract business insights related to customer purchasing behavior, music preferences, and revenue trends.

The dataset contains multiple interconnected tables such as customers, artists, albums, tracks, invoices, and genres. By applying SQL queries, meaningful insights are derived to support data-driven decision making in the music industry.

## Database Schema
The database consists of 11 relational tables:
| Table         | Description             |
| ------------- | ----------------------- |
| Genre         | Music genre categories  |
| MediaType     | Media format of tracks  |
| Employee      | Store employees         |
| Customer      | Customer details        |
| Artist        | Artist information      |
| Album         | Album details           |
| Track         | Individual music tracks |
| Invoice       | Purchase invoices       |
| InvoiceLine   | Items within invoices   |
| Playlist      | Playlist information    |
| PlaylistTrack | Track-playlist mapping  |

The schema demonstrates one-to-many and many-to-many relationships between entities.

## Business Problem Analysis

- Who is the senior-most employee based on job title?
- Which countries generate the most invoices?
- What are the top 3 highest invoice totals?
- Which city generates the highest revenue?
- Who is the best customer based on total spending?
- Who are the Rock music listeners?
- Which artists have the most Rock tracks?
- Which songs are longer than the average song length?
- How much does each customer spend on artists?
- What is the most popular genre in each country?
- Who is the top customer in each country?

## Key Insights

- The USA generates the highest number of invoices.
- Rock music dominates customer purchases.
- Certain cities generate significantly higher revenue.
- A small percentage of customers contribute most sales.
- Popular artists strongly influence music purchasing patterns.


## Skills Applied
- SQL Joins
- Aggregations & Group By
- Subqueires
- Data Filtering
- Data Analysis

## Learning Outcomes
- Understanding relational database schema
- Writing complex SQL queries
- Data exploration using joins and aggregations
- Extracting actionable business insights from data
