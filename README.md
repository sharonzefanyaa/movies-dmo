# movies-dmo

**Q1:** Create a directory in verulam-blue directory named YourStudentID-YourName. Display lists files in verulam-blue directory.

Note This will be your WORKINGDIRECTORY for completing below questions.

**Q2:** Move folder data into your working directory and display lists files in it

**Q3:** Show the first 10 contents of movies.csv file

**Q4:** Display number of directory, number of files and file sizes of your working directory

**Q5:** Create 3 dataframes from CSV filesand get a glimpse of the data.

**Q6:** Rename the following columns using operation for structured Transformation.
a. [movies dataframe] --> Rename movieId with mId
b. [rating dataframe] --> Rename movieId with mrId & userId with ruId
c. [tags dataframe] --> Rename userId with tuId

**Q7:** Register the data frames as 3 SQL tables.

**Q8:** Combine all records from three tables into one, named df. You just need records whenever movieId values from movies table are matching with movieId from rating and tag tables as well as userId values from rating table are matching with those in tag table, using an SQL Query

**Q9:** Remove the specified columns from dataframes mrId, movieId(from tags dataframe), timestamp, and tuId. Then, register the dataframe as an SQL table named df1

**Q10:** select the 10th most rated 5 star movies in a decresing count of times the movie got 5 star rating, using an SQL query

**Q11:** Which user gave most '5' ratings? Return the userID and number of ratings, using an SQL query

**Q12:** check the users that have rated the most and the least number of movies, using an SQL Query

**Q13:** Get a distinct list of all movie titles that are five-star rated in the Crime/Drama genre, using an SQL Query

**Q14:** Get the movie titles tagged with 'Disney' with minimum three-star rated in the Adventure genre, the number of ratings for each movie, ordered by the highest rating, using an SQL Query

**Q15:** Get a sorted count of the number of people who gave each Crime/Thriller movie a four-star or more rating, using an SQL Query
