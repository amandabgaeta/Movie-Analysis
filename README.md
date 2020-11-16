# Microsoft Movie Analysis

## Introduction

Microsoft wants to start their own movie production studio, but they do not have the movie knowledge that they need to start. These files encompass data sources, full analysis, visualizations, and presentation of recommendations for Microsoft.

## Objectives

Give Microsoft an understanding of the movie landscape of the last 10 years and give them pointed recommendations based on answering the following questions

* Question 1: What were the top movie genres made in the 2010s?
* Question 2: What is the best month to release a movie for highest worldwide gross?
* Question 3: Of movies that breakeven (ROI >= 1), what genres are most represented?
* Question 4: Based on production budget and average ratings, what genres are the best investments?
* Question 5: For these breakeven movies that fall into these genres, what is the recommended runtime and who are the highest rated directors?

### The Data

In this folder you will find:
* analysisWalkthrough - walks through creating the base dataset via merging/joining and cleansing as well as answering each of the above questions. Easily find analysis according to a question by using "Find" and searching for "Question #"

* presentation.pdf - PDF of powerpoint slides for Microsoft presentation on answering the above questions and recommendations based off the data analysis answering those questions.

Additional folders include:
* images - holds all visualizations. Those in immediate folder are visualizations used in final Microsoft presentation. There is an additional subfolder 'prod_budg_by_gross_genre' for additional scatterplot visualizations of production budget by worldwide gross that highlights each genre. Saved these as they could be of interest in further exploring.

* rawData - holds single file for rt_movie_info. Had challenges unzipping so saved separate csv for each of use. It is a repeat of the file in 'zippedData'. The folder 'zippedData' has movie datasets from: Box Office Mojo, IMDB, Rotten Tomatoes, TheMovieDB.org, and The Numbers. Although only IMDB And the Numbers is used in the 'analysisWalkthrough.ipynb' file, all of these are explored in scratchWork

* scratchWork - holds file discovery and different approaches taken to get to final direction of analysis. Order of exploration was: 'File_Discovery_Gross_vs_Budget_and_Prod_ROI_Analysis.ipynb', 'RT_Reviews_Analysis_IMDB_Basics_Merge.ipynb', 'IMDB_Tables_Insights.ipynb', and finally 'Larger_Base_Dataset_using_all_IMDB.ipynb'. The last file gets to the join/merge patterns used in 'analysisWalkthrough.ipynb'


## Key links and files

1. A **GitHub repository** 
Found at https://github.com/amandabgaeta/Movie-Analysis
2. A **Jupyter Notebook** 
File name: 'analysisWalkthrough.ipynb'
3. A non-technical presentation **slide deck**  
File name: presentation.pdf

## Summary

Used IMDB and The Numbers data to answer the questions posed in the objectives. Answers and recommendations are as follows:

Question 1: What were the top movie genres made in the 2010s?
Drama, Documentary, Comedy, Thriller, and Horror were top movie genres made in the 2010s

Question 2: What is the best month to release a movie for highest worldwide gross?
June and November are best release months at $27B and $27.5B respectively

Question 3: Of movies that breakeven (ROI >= 1), what genres are most represented?
Drama, Comedy, Action, Adventure, and Thriller are top genres represented in breakeven films

Question 4: Based on production budget and average ratings, what genres are the best investments?
Dramas and Comedies are the best investment at $17MM and $25MM

Question 5: For these breakeven movies that fall into these genres, what is the recommended runtime and who are the highest rated directors?
Drama, Comedy, Action, Adventure, and Thriller should run between 1.75-2 hours. Director names are global and should be further researched after Microsoft makes more business decisions.

## Next Steps and Future Work

Next steps include business decisions by Microsoft like:
* Target audience definition : Location, Language
* Theater release, streaming, or both in full lifecycle
* Budgeting and initial launches: Banner movie, goal movie portfolio

Further analysis would include:
* If decide on streaming, gather data from top streaming services
* Top writers per top genre
* Highest rated actors in top genres and their known for characters
