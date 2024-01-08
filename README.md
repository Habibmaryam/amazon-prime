# Amazon-prime
Amazon Prime Movie Report Analysis
---
# Introduction 
The dataset is called the **Amazon Prime titles** which consists of rows and columns and entries regarding movies and details as regards the release date, country of release, title, and so forth.

Each entry is identified by a unique identifier and tells us about the name of the movie, the director of the movie, the location on release, year added, date added, casts, ratings, duration, genre, and what the movie is all about. 

**Explanation of each column**
The show_id is a unique identifier that is used for each record in each row.
The name of the movie is the title of the movie
The director is in charge of directing the movie
The location is the location where the movie was made.
The cast are the actors featured in the movie
The first ratings are the age ratings
The second rating is the customer rating after viewing the movies
The year added is the year it was added to the Amazon Prime platform ready for viewing
The release date is the date on which the movie was released for public viewing

---
# Business Questions

Some of the potential business questions that can be used to analyze the Amazon Prime titled dataset include;

- The number of countries where the movies on the Amazon Prime platform were made.
- Number of movies added on the 31st of March, 2021 
- Directors who directed movies after the year 2018.
- Number of Age rating movies 13+
- Number of comedy dramas, their year of release, and their duration.

  ---
  # Data Cleaning and data wrangling

This report will address the data quality issues found in the Amazon Prime title dataset.

Firstly, the cells C20 and D20 were merged, making it impossible to view the data entries in those cells. Unmerging the cells will solve this issue.

Also, the director name column should be divided into the “First name” and “Last name” columns. Cell D18 should have a director name in it because every movie has a director. 

The data format does not use a defined data format under the date_added. That is, integer and string formats were used. The year is recorded as XX instead of XXXX. Additionally, there were empty dates under the date_added column which is unusual, knowing that a movie should have a release date. 

There were also duplicates spotted in the dataset, For instance, the type of movie, the date_added, and the country columns all contain duplicate values. These could pose a problem because it couldn't necessarily be duplicated if we look at each row. However, there were no duplicates in this dataset.

The cast and description columns are rather ambiguous and also irrelevant column.

The data has a lot of white and empty spaces.

There were inconsistencies in the duration column where some entries were recorded as “seasons” instead of “min”.
The country had too many empty cells which would alter the analysis process.

---
# Analysis

**The number of countries where the movies on the Amazon Prime platform were made.**
