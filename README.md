# Movie_Revenue
Project to determine effects of budget and summer release of movies to their revenue.

This project uses Google Colab to import a csv file from Kaggle.com.
The data set is cleaned by using reducing data to usable data.
The first filter is to use only movies from 2011 to 2017. This provides a list of 1221 movies.
Next was to eliminate all movies whose budget and revenue are listed as 0. This ultimately reduced the data size to 785 movies.
Finally, a new column was created to determine if the movie was released in the summer months.

Using the filtered data set, we start the first analysis comparing budget and revenue.
A scatterplot was created and correlation coefficient and p-value was calculated to support or reject the null hypothesis.
Ho: There is no positive, direct variation between budget and revenue.
Ha: There is a positive, direct variation between budget and revenue.

The second analysis was the creation of a box plot and calculation of the p-value to support or reject the null hypothesis.
Ho: Movies released in the summer months have no impact on revenue.
Ha: Movies released in the summer months have an impact on revenue.

A bonus analysis was conducted that combined budget, summer release, and revenue.
A updated scatterplot was made showing which movies were summer releases.
The correlation coefficien was calculated for summer and non-summer movies.

Results and conclusions were summarized.
