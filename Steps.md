# These are the major steps that need to be followed in order to perform the operation

- Create a DataFrame named movies containing all details.
- Groupby title of above DataFrame and put them into a DataFrame calles "Ratings".
- Ratings contains:
  - mean() operation on the groupby object.
  - count() operation on the groupby object.
- Create a pivot table containing individual ratings by users to each movie, name it "Movie_Matrix".
- Choose a movie and find all the ratings given to the movie from above pivot table ("Movie_Matrix").
- Find co-relation of the above movie ratings to all the movie ratings listed in pivot table.
- 'Join' the above Co-relation table to the corresponding number of ratings.
- Filter the values such as number of ratings given to  a movie.
- Sort values in descending order and you have the most co-relating movies.
