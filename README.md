# nosql-challenge


This challenge contains three parts in which I import the database and read it in a jupyter notebook, update the database and conduct exploratory analysis.

In part one of the challenge I imported the data from the resources folder and then open it up in jupyter notebook using Mongolcient from the pymongo library as a connection betweeen MongoDB and python. Once initial setup was completed I verified that the (Uk food) database and (establishments) collection was accessible. 

In part two of the challenge I updated the database and added a new restaurant and updated BussinessTypeID. Also I made updates to the database by changing data type for certain fields

In part three of the challenge  I explored the dataset based on RatingValue using aggretion functions. Once results were found they were placed in a DataFrame. The following questions were answer during the analysis:
Which establishments have a hygiene score equal to 20?
The results were placed in a Dataframe and there are 41 establishments with with a hygiene score equal to 20.
Which establishments in London have a RatingValue greater than or equal to 4?
The results were placed in a Dataframe and there are 33 establishments in London with a RatingValue greater than or equal to 4. 
What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
The results were placed in a Dataframe and the BusinessName of the five establishments found are 'Howe and Co Fish and Chips - Van 17', 'Atlantic Fish Bar', 'Plumstead Manor Nursery', 'Iceland' and 'Volunteer'.
How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest, and print out the top ten local authority areas.
The results were placed in a dataFrame and the top ten local authrity areas are Thanet, Greenwich, Maidstone, Newham, Swale, Chelmsford, Medway, Bexley, Southend-On-Sea and Tendring. 
