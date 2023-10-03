# NoSQL_Challenge
NoSQL


**Part 1**

The first part of the challenge I had to add a new restaurant to an existing database for the UK Food Standards Agency.  The name of the restaurant is Penang Flavours, the data was provided to me in the challenge. 
After that, I utilized the "query" and "fields" functions related to SQL.  

Per the request, all establishments located in Dover were removed from the database utilizing the "delete_many" function.

Lastly, I changed string format into integer via the "set" function to a specific set of values.



**Part 2**

I used the "find_one" function to ensure I read in the data correctly.  The worst thing to happen is to have bad data or an incorrect database. 
I had to pull a specific query in relation to Hygiene Scores within the database and convert it into a Dataframe. 

![hygiene](https://github.com/amshanaa/nosql-challenge/assets/136298119/56253412-c78e-422d-8909-0e03c3255c24)

The request after required the used of "regular expression" and "greater than" functions.  I was able to find 33 documents that met the criteria.  I was then able to convert it into a DataFrame (syntax is key, lol).  

The pipeline was the hardest as I am not comfortable twith how it works.  From spending 2+ hours on this, it was a lot of review of video.  Match Query is like a regular query that lets you filter data, but it has to be used in a specific manner to aggregate the data.  Grouping requires an Id, for this request Local Authority Name was the "_id". Since the data was stored in a list, I used the range function to Print the results. 
