### _Personal dataset project for the semester, work in progress_
# Motivating Questions

Initial Questions:
1. Are there any notable keywords or phrases that Pitchfork tends to use for negative reviews? How
about for positive or average reviews?
2. Over the years cataloged do any genres show trends of becoming more positively or negatively reviewed?
Any displayed biases towards genres or specific artists?
3. What are the top rated and worst rated artists across their discography? Do they have any commonalities?

Final focus:
  -

# Data Process

I sourced my data from David Nolan's web scrape of all Pitchfork reviews from 1999-2017
  
  https://www.kaggle.com/nolanbconaway/pitchfork-data
  
I exported the individual tables through RazorSQL, and used RStudio to compile. Cleaning involved filtering out duplicate reviews, and filling missing data. I compiled all the albums without genre tags as "Miscellaneous", and albums missing a release date I copied over the Pitchfork review year. I split the datasets according to genre to perform further analysis. 

# Visualization

![Pitchfork Average Scores](https://github.com/ElishaPhillips/DATA-115-Personal-Dataset-Project/blob/main/Analysis/Main/PitchforkAverageScoresGenre.png)

The initial overview by album release year shows how albums from previous years selected for review following Pitchfork's inception in 1999 trend towards a higher rating. The outliers are worthy of further analysis, such as Metal reviews in 2001 and 1989, and Experimental in 2000. Pop & R&B in 1970 and 1978 seem worthy of a closer look as well. 

![Pitchfork Score Distribution Boxplot](https://github.com/ElishaPhillips/DATA-115-Personal-Dataset-Project/blob/main/Analysis/Main/PitchforkGenreScoreBoxplot.png)

To investigate the distributional characteristics, I made a boxplot, sorted by genre. The median scores all hover around 7.0-7.5, and the overall distribution is either centered or slightly left skewed. Rock clearly holds the largest number of scores, and Global trends towards the highest median while being the lowest sample size.
# Analytical Technique

# Sentiment Analysis 


