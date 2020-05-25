# Analyzing IMDB Movies

![image](https://s.studiobinder.com/wp-content/uploads/2019/06/Best-M-Night-Shyamalan-Movies-and-Directing-Style-StudioBinder.jpg)

The Internet Movie Database (IMDb) is a website that serves as an online database of world cinema. This website contains a large number of public data on films such as the title of the film, the year of release of the film, the genre of the film, the audience, the rating of critics, the duration of the film, the summary of the film, actors, directors and much more. Faced with the large amount of data available on this site, I thought that it would be interesting to analyze the movies data on the IMDb website between the year 2000 and the year 2017.

We find the selected data:
Movie title -> Movie
Genre of the movie -> Genre
Movie duration (in minutes) -> timeMin
Release year of the film -> Year
Number of public votes -> Vote
Public rating (score out of 10) -> audienceRating
Critics rating (score out of 100) -> criticRating
Movie Gross (in millions of dollars) -> grossMillions

We can see on the image above, that I recovered 4583 entries (lines) with 8 columns (one type of data for each column). For each column of data (audienceRating, Genre, etc.), I do not have any missing values (non-null) and the typing of the data seems consistent, for example, I have a float for the public note ( audienceRating), an integer for the year and the number of votes. However, the Genre and Movie columns are by definition strings and Python interprets them as object type. To be able to use and visualize these two data Genre and Movie, I have to type them in category.

Statistical modeling of data
As said before, I selected the following data for the statistical modeling:
Movie title -> Movie
Genre of the movie -> Genre
Movie duration (in minutes) -> timeMin
Release year of the film -> Year
Number of public votes -> Vote
Public rating (score out of 10) -> audienceRating
Critics rating (score out of 100) -> criticRating
Movie Gross (in millions of dollars) -> grossMillions


