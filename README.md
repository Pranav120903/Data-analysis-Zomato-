# Data-analysis-Zomato-
Explored and Analyzed Using SQL Server

The Zomato dataset, containing over 9,000 entries, includes information such as Restaurant ID, Name, City, Location, Cuisines, and more. The objective was to clean, explore, and derive meaningful insights using SQL.

Data Exploration Highlights:
Reviewed column details, data types, and constraints.

Removed duplicates and irrelevant columns.

Merged tables using CountryCode to include CountryName.

Corrected misspelled city names.

Used window functions for rolling restaurant counts.

Computed min, max, and average values for votes, ratings, and currency.

Categorized restaurants based on rating levels.

Key Findings:
90.67% of the data is from India, followed by the USA (4.45%).

Only India (28%) and UAE (46%) offer online delivery.

Connaught Place, New Delhi has the highest number of restaurants (122); North Indian is the most common cuisine.

Only 54 of those 122 offer table booking.

Average rating is 3.9 for restaurants with table booking vs 3.7 without.

The best moderately priced Indian restaurant is "India Restaurant" in Kolkata (Restaurant ID: 20747).
