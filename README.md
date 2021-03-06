# Movie_Market_Analysis_Project

# Authors:

MS Consulting Incorporated
Sam Videlock & Mayank Phanse

# Project Goals:
  
Provide actionable insgights and recommendations to Microsft based on data analytics.
    
# Presentation Link

https://www.canva.com/design/DADtMN9FIdo/TjhF-BUfcsJjRCGahlCRnA/view?utm_content=DADtMN9FIdo&utm_campaign=designshare&utm_medium=link&utm_source=sharebutton

# Findings:

  - Franchisied movies significantly outperferm their non-franchise counterparts. We recommend purchasing established franchises as well as creating orginal content
  - Spending more typically leads to higher profits, with the highest potential budget between $200 - $250 Million.
  - When you release your film has a major impact on total sales. Releasing between April - June will give you the best chance of success, with the Q4 dates in second place.
  
# Procedure:
## Data Gather 
### Data Set 1:
  1. Pull data from: https://www.the-numbers.com/movie/budgets/all (saved as 'full_data')
      This file contains roughly 600 of the highest budgeted movies, we adjusted our data to only contain information from movie release dates from 2006 - mid 2019
  2. Read that csv into a Jupyter Notebook, ours is called 'Movies_1.ipynb'
  3. When looking at the dataframe, we had some good inital data on movie title, gross worldwide sales, and budget, but we had little other data
  4. We then wanted to connect to the movie DB website API (https://developers.themoviedb.org/3/getting-started/introduction) in order to pull down additional details about the movie titles like genre, rating, release date
  5. There is data manipulation that this part contianed, and you will need to refer to that python file in order to see the work performed. Two dataframes were turned into csv's.
  6. In the next next three python files called 'Combining DataFrames_2' , 'GenreCorrection_3' & 'Month_data_4' we are performing different tasks to clean up and organize the data, refer to the files for specifics. Descriptions are provided in each python file. 
  7. Our final file was saved as 'table_month_roi.csv'
  
### Data Set 2:
  1. Pull data from: https://www.the-numbers.com/box-office-records/worldwide/all-movies/cumulative/released-in-2018
  2. We then did this for 2014 - 2017 as well as the link above which contains 2018
  3. We had to do some self classification in order to identify franchise movies and non-franchise movies for the Top 7 grossing of each category in each year. This can be found in the file 'franchise_movie_data_with_movies.csv'
  
## Creating Figures
  1. For the budget vs. profit boxplot, this was created in python in the file 'visual_proj1'. Refer to theat file for instruction and code on creation of that visual.
  2. The other visuals were created in Power BI and can be found in the file names 'monthly_visualization' & 'top_7_franchise'
  3. Canva was used for the presentation deck, and the link is above where all visualizations can be found. 
 
  

