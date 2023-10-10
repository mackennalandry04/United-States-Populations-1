# United-States-Populations-1

### Goal of Project 
The goal of this project is to analyze demographic data in U.S. states to identify trends over the past decade (data from the 2010 and 2020 census). This analysis also explores how population impacts congressional representations, including visualizations and insights. With the visualizations and insights, we can gain a better understanding of population distributions and dynamics around the U.S.  

### API Doctumentation
I used the BeautifulSoup API documentation that helped me parse and extract my data from the webpage. 

### License of data 
The population data that was used in this project was obtained from [Wikepedia U.S. States by Popualation](https://simple.wikipedia.org/wiki/List_of_U.S._states_by_population). This data is licensed under Creative Commons Attribution-Sharealike 4.0 International License (CC-BY-SA) and the GNU Free Documentation License (GFDL). Under the Creative Commons Attribution-Sharealike 4.0 International License (CC-BY-SA), users are free to use, modify, and distribute the data as long as proper attribution is provided. The GNU Free Documentation License (GFDL) allows for reuse and modification. These two license cover everything done with this data. 

### Data types and descriptions 
_State_(String): The name of the U.S. State. \
_Rank_(integer): Numerical representation of a state's position relative to others based on its population. \
_Population in 2020_(float): The population count of the state in the year 2020.\
_Population in 2010_(float): The population count of the state in the year 2010.\
_Growth_(float): The percentage growth in population from 2010 to 2020. \
_Absolute Change_ (float): Represents the magnitude of population change between 2010 and 2020. \
_Seats in HOR (House of Representatives)_ (float): The number of seats each state has in the House of Representatives. 

### Data at Data.world
Here is my data on dataworld with a project summary and data dictionary: https://data.world/mackennalandry/us-population-data-curation-and-analysis


### Potential Issues 
There were not any extreme issues when I did my data analysis, but there were some pretty extreme outliers that affected the distribution. I chose to investigate them and realized they were states like California and Texas that caused the distribution to have outliers. These states have much larger populations which makes sense with their retropective sizes as well.

### Resources 
This was one of my first times doing data analysis like this, so I needed to do some research. Here are some of my resources 

Big Data Guy. (2018, May 1). _Web Scraping Wikipedia Tables using Beautiful Soup and Python_. Medium. https://medium.com/analytics-vidhya/web-scraping-wiki-tables-using-beautifulsoup-and-python-6b9ea26d8722

GeeksforGeeks. (2020, December 2). _Creating horizontal bar charts using pandas_. GeeksforGeeks. https://www.geeksforgeeks.org/creating-horizontal-bar-charts-using-pandas/ 

