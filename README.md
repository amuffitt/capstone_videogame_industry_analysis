# Background

This Python Jupyter notebook and associated Tableau dashboard were created as part of a Capstone project for the Data Analytics Career Track program at Springboard (designed in partnership with Microsoft).

The data is focused on video game sales and critic/user ratings (when available) for video games that were released from 1995-2016. To add some business context to the dataset for the project, a fictitious scenario was created where a video game store would like to showcase more historical data for video games enthusiasts that visit the store as an added attraction and source of information.   

# Dataset

The data is from a Kaggle.com dataset at https://www.kaggle.com/rush4ratio/video-game-sales-with-ratings/ and based on a previous scrape of Vgchartz.com that contained video game data on almost 17k games from 1980-2016. It later added corresponding critic/user scores and ratings from Metacritic for ~6,900 games. While the original data description said that only games with over 100,000 units sold were included, it appears from the data that games with over 10,000 units are included.  

The date range chosen for this specific project is 1995-2016 because available data before the mid-nineties was lower likely due to a) not as much related sales data being logged for games during those years and b) the overall industry was less widely popular and mature.

Note that data was collected in late 2016 so 2016 may be missing some late year sales and releases and should be considered “incomplete”. The dataset has not been updated since 2016 so sales after that are not reflected.

# Jupyter notebook (Capstone2_Video_Game_Sales.ipynb file)

The dataset provides a nice opportunity to learn and showcase various ways in Python, Matplotlib, Numpy, Seaborn, etc to compute and visually showcase data. The old saying goes "There are multiple ways to skin a cat" and that's the case here. These graphs and queries show certain specific ways but they of course aren't the only way.

One technical theme of interest that came out of generating this data in Python was producing an animated 'slideshow' that would show multiple pieces of information per year over 21 years rather than in those cases trying to crowd everything into one graph. This was an opportunity to learn/discover the 'FuncAnimation' functionality from the Animation library that can be used to repeatedly call functions to produce different animations in Python. In this fictitious case, the video game store could have these different animations playing in the store as an added attraction.

# Tableau Dashboards

Using the same dataset, 2 associated Tableau dashboards were built to allow anyone to view the data and trends (in this scenario, allow in-store users to dynamically view and filter various trends and metrics related to video game platforms and release years of interest.)

The dashboards can be found at https://public.tableau.com/profile/adam.muffitt#!/vizhome/Capstone2VideoGameAnalysis/VideoGameOverallDashboard 

  - Video Game ‘Overall’ Dashboard – View game release volume per year, regional unit sales per year, Top 10 publishers (in global unit sales), highest selling games, game release volume by genre, and a chart that shows the percentage of unit sales each platform made up each year.  All charts except the last are filterable for any desired year or game platform.
  
  - Video Game ‘Platform’ Dashboard – A related dashboard with some different charts that show either all platforms or a single filtered platform.  View a combo chart of release volume/unit sales by year, top games by critic score, release volume by genre, and a scatterplot of critic score vs user score sized by global sales that shows related information on rollover for individual games.  

# Powerpoint Deck (Capstone 2 Slide Deck.pptx)
This was a final deck describing the project created for the Springboard class and presented to a mentor at Springboard.
