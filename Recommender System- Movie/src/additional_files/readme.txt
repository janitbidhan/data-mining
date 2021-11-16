-----
Additional Files
-----

   
   * movie_genres.dat
   
        This file contains the genres of the movies.
   
   * movie_directors.dat
   
   	This file contains the directors of the movies.
   
   * movie_actors.dat
   
   	This file contains the main actores and actresses of the movies.
   	
   	A ranking is given to the actors of each movie according to the order in which 
   	they appear on the movie IMDb cast web page.
   
   
   * tags.dat
   
   	This file contains the set of tags available in the dataset.
   
   * user_taggedmovies.dat 
   
        These files contain the tag assignments of the movies provided by each particular user.
        
   
   * movie_tags.dat
   
        This file contains the tags assigned to the movies, and the number of times 
        the tags were assigned to each movie.
   

-----------
Data format
-----------

   The data is formatted one entry per line as follows (tab separated, "\t"):


   * movie_genres.dat
   
        movieID	\t genre

        Example:
        1	Adventure

   * movie_directors.dat

        movieID \t directorID \t directorName

        Example:
        1	john_lasseter	John Lasseter
   
   * movie_actors.dat

        movieID \t actorID \t actorName \t ranking

        Example:
        1	annie_potts	Annie Potts	10
   
   
   * tags.dat

        id \t value

        Example:
        1	earth

   * movie_tags.dat

        movieID \t tagID \t tagWeight

        Example:
        1	13	3
   
        
   * user_taggedmovies.dat

        userID \t movieID \t tagID 
        Example:
        75	353	5290	   

   * train.dat

        userID \t movieID \t rating

        Example:
        75	3	1	


   * test.dat

        userID \t movieID 

        Example:
        75	3	
