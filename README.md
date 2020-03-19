# Querying_MovieLens_Data

This week you will be using the MovieLens 1 million ratings dataset. By the time you are finished with this assignment, you will have another SQL database and NoSQL database to use in other classes or for projects.

Broadly, this assignment will follow the FTE&#39;s progression:

- Load MovieLens tables into a SQL database (good time to find that &quot;multiple insert&quot;)
- Create a query to retrieve reviews into a cursor
- Create a dataclass that represents a movie review
- Translate rows of the cursor into a list of MovieReview objects
- Translate the list of MovieReviews into a list of dictionaries
- Load the list of dictionaries into TinyDB (using insert\_multiple() )

There is one important point that will need to be addressed:

- MovieLens is comprised of 3 tables:
  - Users
  - Movies
  - Reviews
