# Strategic Recommendations based on Data Analysis on Movie Dataset

This analysis provides two distinct investment strategies primarily dependent on the client's access to capital and risk tolerance. The 1st strategy provides less-upside but more consistent returns on large capital investments. The 2nd strategy provides higher-risk 

### Strategy #1: Capital Intensive/Risk Averse

- The capital-intensive Animation & Adventure categories provide the highest profit of any genre
- Animation & Adventure genres provide some of the highest median equity multiples with low relative downside
#### Recommendations: 
- Target the Animation & Adventure Genres
- Target a summertime release
- Target longer runtimes 

### Strategy #2: Capital-Efficient/Higher Risk
- The capital-efficient categories of Horror & Mystery provide slightly lower median equity multiples than more capital-intensive titles, however, they are riskier and offer substantially more upside than other genres
#### Recommendations: 
- Target the Horror & Mystery Genres
- Target a summertime release
- Target shorter runtimes 

## The Dataset
A CSV file (‘tn.movie_budgets.cvs’) that contains information about movie release dates, movies, production budget, domestic gross, and worldwide gross
A dataset was extracted using SQLite and collected information from the IMDB movie database.

## Supporting Evidence 

![CORRELATION MAP CHART](https://github.com/gloriapintado/DataAnalysisMovie/blob/main/images/Correlationplot.png)

There is a strong .68 Correlation between Production Budget and Profit. This indicates that, generally, higher budget movies will garner higher profits
There is a very weak negative -0.058 Correlation Between Production Budget and Equity Multiple. This indicates that larger investments will generate large profits, but the rate of return is unrelated to production_budget or the size of investment¶

![GROSS PROFIT BARCHART](https://github.com/gloriapintado/DataAnalysisMovie/blob/main/images/WorldwideGrossProfitByGenre.png)

The Production Budget and Gross Profit follow very similar trends indicating the importance of production budget in predicting gross profit. Adventure, Animation, and Sci-Fi are the top genres in terms of spending and profit

![Equity Multiple By Genre Boxplot](https://github.com/gloriapintado/DataAnalysisMovie/blob/main/images/BoxPlotGenres.png)

Mean Equity Multiples, however, are substantially higher in the Horror, Mystery, and Thriller Categories all of which are in the relative mid-lower levels of production budgets

The Boxplots demonstrate the median capital required to enter in the highest-profit generating categories such as animation, adventure and action is substantially higher than the higher end of the Horror/Mystery categories.

The Animation, Adventure and Action categories have substantially higher floors in terms of equity multiples than the higher-risk categories of Horror and Mystery. 

Horror and Mystery cannot match the gross returns of the more capital-intensive genres but offer riskier but subtantially higher returns if the movie performs above the mean.

![Mean Monthly Worldwide Profit](https://github.com/gloriapintado/DataAnalysisMovie/blob/main/images/MeanMonthlyWorldwideProfit.png)

![Monthly Worldwide Equity Multiple](https://github.com/gloriapintado/DataAnalysisMovie/blob/main/images/MonthlyWorldwideEquityMultiple.png)

The data demonstrates that, historically, summer releases have outperformed in terms of both gross profit and equity multiples. In particular, the month of June seems to offer the best performance across the two aforementioned metrics

## Next Steps
Incorporate marketing & distribution spending data to provide a more comphrensive view of gross profits and equity multiples. 

Additionally, conduct analysis on a more recently collected dataset to see if these trends are durable into 2023
