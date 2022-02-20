# surfs_up
Using SQLite (local database) and SQLAlchemy (SQL query tool) to develop a weather app to make a business decision regarding opening a surf and ice cream shop on Oahu, an island in Hawaii.  Finally, a Flask application was created to display the data via a webpage for end users.

## Overview of the Analysis
I'm looking to open and surf and ice cream shop in Oahu, Hawaii and have been in contact with a potential investor.  W. Avy is the potential investor, who had tried opening a surf shop years ago but failed due to the weather.  Specifically, he had not considered the amount of precipitation where his shop was located and he ended up closing his shop.  W. Avy is interested in the project, but he is asking for temperature and precipitation information to present to his board before a business decision is made.

The data was stored in SQLite as hawaii.sqlite and SQLAlchemy was used to query the database.  The queried information regarding precipitation and temperature was then converted to a dataframe for further analysis.  Analysis included descriptive statistics and plotting graphs.

### Resources
Data Source:

  * hawaii.sqlite

Code:

  * climate_analysis.ipynb
  * SurfsUp_Challenge.ipynb

Software:

  * Python 3.7.6
  * Pandas 1.3.5
  * SQLAlchemy
  * Jupyter Notebook

## Results
The results will include data and analysis of precipitation and temperature.

### Precipitation Analysis
The reason why W. Avy's surf shop failed was primarly due to the amount of precipitation that the location of the shop recieved.  Based on an analysis of data that spanned the timeframe of August 23, 2016 through August 23, 3017, Oahu recieved precipitation approximately **18%** of the time, and thus **it was dry 82% of the time**.  When considering precipation alone, Oahu would be a good location because it is without precipitation 82% of the time.

Descriptive statistics regarding precipitation in Oahu:

![image](https://user-images.githubusercontent.com/94148420/154858477-92d1a1b4-de5f-409e-87c7-0026fe86e42d.png)

Graph depicting the precipitation measures and date in Oahu:

![image](https://user-images.githubusercontent.com/94148420/154858600-3b0f2e9e-f960-4826-a1a1-e48735f2e971.png)

### Temperature Analysis
Further analysis regarding year round temperature data on Oahu was performed pulling data for the months of June and December.  Below are the summary statistics graphs for June and December.

**June Temperature Statistics & Graph**

![image](https://user-images.githubusercontent.com/94148420/154859166-09542c49-8a98-4f7e-a607-ee66764bc4ee.png)

![image](https://user-images.githubusercontent.com/94148420/154859251-e28fa278-ffe1-4c5f-a3eb-b3500522c5f1.png)

**December Temperature Statistics & Graph**

![image](https://user-images.githubusercontent.com/94148420/154859327-849cb58c-d1bb-4d25-82fc-9fce3fc1e79b.png)

![image](https://user-images.githubusercontent.com/94148420/154859367-bdf831cd-ea79-45ef-ba70-b2efddaa50e9.png)





## Summary


