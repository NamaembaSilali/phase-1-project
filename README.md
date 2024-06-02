# ANALYSIS FOR MICROSOFT'S NEW MOVIE STUDIO

## Project Overview

For this project, I used Exploratory Data analysis to derive meaningful insights for Microsoft's New Movie Studio. 
The main objective of this chapter is to provide an overview of the current state of research on the topic. 
Microsoft is taking a giant leap into the entertainment industry with a new movie studio. But before it does, they need strategic insights for a successful venture. I have been tasked to leverage data insights to guide their new venture. This project will strongly be aided by performing exploratory data analysis and the focus will be understanding the performance dynamics of movie genres, release dates and budgets in order to derive actionable recommendations for the strategic planning of Microsoft's new movie studio. 
To achieve this, my analysis will follow this structured approach:
1. Data Collection where I will compile the relevant datasets from different data sources that include the movie genres, dates of release and budgets.
2. Exploratory Data Analysis (EDA) to identify general patterns in the data.
3. Recommendations based on the data insights to help derive meaningful strategies before Microsoft opens its new venture.

### Business Understanding for Microsoft's new movie studio
Since Microsoft is new to the industry, I have identified the key problems that need to be addressed so that the new business venture can be a success.

This analysis will be based on the following factors:
1. Which genres perform well in the film industry? Perform analysis to determine which genres are profitable and have a high demand. This will help Microsoft to focus on the right genre to invest in.
2. Is there a correlation between a film budget and the revenue? Analyze the relationship between the budget and revenue of a film to determine if investing in high budget films is profitable. This will help Microsoft to determine the budget optimization for their films.
3. What are the trends? Is there any particular time of the year that is more profitable for film release? Identify profitable film release windows by analyzing historical release dates. This will help Microsoft to determine the best time to release their films.

## Data Understanding
I utilized four data sources. The data I used for this analysis are from the following sources:
1. Data Source 1: bom.movie_gross.csv.gz, box office mojo that has the gross earnings of the movies.
2. Data Source 2:tmdb.movies.csv.gz that contain data about the release dates of the movies.
3. Data Source 3: rt.movie_info.tsv.gz that contain the genre of the movies.
4. Data Source 4: tn movies that has information about gross earnings.
The data was cleaned and merged to create a comprehensive dataset for analysis.
The dataset contains the following variables: Genres, Release dates, production budgets, worldwide gross, movie title, domestic gross and foreign gross.

## Methods
The methods used in this analysis include descriptive analysis and use of visualizations to find the most popular genres, the correlation between budgets and revenues and the overall distributions over the months.
The analysis was done using Python programming language and its libraries such as Pandas, NumPy, Matplotlib and Seaborn.

## Results
The results of the analysis are as follows:
1. The most profitable genres are Drama, Comedy, Comedy|Drama, Drama|Mystery and Suspense.
2. There is a positive correlation between the budget and revenue of a film. The correlation coefficient is 0.639. This means that the higher the production budget, the higher the revenue.
3. The most profitable months for film release are June, July, November and December.
The results of this analysis will be used to guide Microsoft's new movie studio in making informed decisions about which genres to invest in, how much to budget for their films and when to release their films for maximum profitability.

## Conclusion

### Recommendations
From the results, here are my recommendations:
1. Microsoft should consider releasing movies that are among the top 10 genres and also coming up with unique subgenres with a blend of the most performing genres. This can help captivate a new audience and broaden the revenue.
2. Budget allocation: Microsoft should consider allocating sufficient budgets for the film production as the correlation coefficient of 0.639 shows a positive correlation between budget allocated and revenues. However, it is important to balance expenditure for better revenues. Invest in high-quality production, marketing, and distribution to ensure the budget translates into higher success.
3. Optimal Release Periods: The most profitable release months are June, July, November and December. Microsoft can opt to do major releases during these periods to capitalize on higher audience turnouts. Microsoft should align its marketing campaigns to build anticipation leading up to these months.

### Additional Strategic Recommendations
1. Diversification: While focusing on the most profitable genres, it's also beneficial for Microsoft to diversify its portfolio to mitigate risks associated with market fluctuations and changing audience preferences. This is by looking at thr emerging genres and coproducing films to target a wider international market.
2. Leveraging data analytics to continuously monitor market trends, audience preferences, and competitor strategies.
3. Microsoft can invest in securing top talent (actors, directors, writers) who can draw audiences and add credibility to your projects.
4. Microsoft can invest in strong marketing campaigns to maximize reach and audience engagement.

