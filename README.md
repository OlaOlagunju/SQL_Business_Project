# Using SQL to guide Business decisions for Chinook

[Full Project Link](https://github.com/OlaOlagunju/SQL_Business_Project/blob/main/Full%20Project%20-%20Data%20Analysis%20using%20SQL%20to%20guide%20Business%20decisions%20for%20Chinook.ipynb)

## Summary
The aim of this project was to explore a modified version of the Chinook database using SQL and answer some business questions. The database is provided as a SQLite database file called 'chinook.db'. It contains information about employees, customers, purchases, and everything to do with the tracks that are on the platform (artists, albums, genres, playlists, etc.).

We answered the following questions:
- Top music genres sold in USA
- Sales performance by country
- Employees sales performance
- Album vs Individual track sales
- Tracks in store and popularity

With regards to genre popularity, the analysis shows that with 53.4% of tracks sold, Rock is the most popular genre on the platform. Rock is followed by Alternative & Punk and Metal, each with about 12% of tracks sold. This is confirmed by the ten artists with the most tracks sold: Queen, Jimmi Hendrix, Red Hot Chili Peppers, Pearl Jam, AC/DC, Guns N' Roses, Foo Fighters, The Rolling Stones, and Metallica. However, considering the four artists that Chinook can potentially bring in, the recommendation is to bring in Red Tone, Slim Jim Bites, and Meteor and the Girls. This recommendation is based on the fact that the genres of these three artists (Punk, Blues, and Pop, respectively) are the most popular of the four options.

![](https://github.com/OlaOlagunju/SQL_Business_Project/blob/main/fig_1.png)
-------------------------------------------------------------------------------

The sales totals attributed to each Sales Support Agent are as follows: Jane Peacock with 1731.51, Margaret Park with 1,584.00, and Steve Johnson with $1,393.92. It is interesting to note that the order in which these employees were hired is the same. In other words, Jane was hired first, then Margaret, and last Steve. Considering this, the sales totals, or rather, the order of sales totals makes sense.

![](https://github.com/OlaOlagunju/SQL_Business_Project/blob/main/fig_2.png)
-------------------------------------------------------------------------------

When considering countries for which to expand marketing efforts in, it makes sense to target countries with large populations and high average lifetime customer values. One country that meets both of these criteria is India. India has a population of over 1.3 billion and customers average lifetime totals of $91.58. Other countries, such as the US, Germany, Brazil, Portugal, and Czech Republic meet one, not both of the criteria.

![](https://github.com/OlaOlagunju/SQL_Business_Project/blob/main/fig_3.png)
-------------------------------------------------------------------------------

Also, we have figured out that album sales make up 19% of all sales but, most importantly, 31% of total revenue. For this reason, it is not recommended to eliminate whole albums from Chinook in favor of single tracks only. Doing so can potentially lead to a loss of a fifth of revenue.

![](https://github.com/OlaOlagunju/SQL_Business_Project/blob/main/fig_4.png)
-------------------------------------------------------------------------------

We also recommended for Chinook to find the most popular tracks in each genre and diversify their store selection to boost sales even more.

![](https://github.com/OlaOlagunju/SQL_Business_Project/blob/main/fig_5.png)
