--------------------
This project is a movie review website that allows users to view and share reviews on movies that are out in the market.
The user is allowed to create a new movie as in add a movie that has not been added to the website yet.
They can choose to read the reviews of a particular movie. A user can also add a review for a movie and at the same time delete their review.

A couple of rules for backend validation are:
1. The movie title must be 3 or more characters long.
2. The name of the reviewer mst be given while writig a review or giving star rating for any movie.
3. While creating a movie, the review for the movie must be provided.
4. The reviewer's name must be at least 3 characters long.
5. The star rating must be 1 to 5 stars. No more no less.
6. The content of the review must be more than 3 characters long.
7. Error messages will be sent to inform the user that the above are not meeting the requirements.

Speaking of the routing and the webpages,
The root route redirects to '/movies' where all the existing movies in the website are displayed. 'movies/new' displays the form where the user can create a new movies and all the requirements must be fullfilled to create the movie. If cancel is pressed, it redirects to the root route. '/movies/:id' displays the existing reviews for any particular movie. '/movies/:id/review' displays the form where a user can add a new review for a particular movies provided all the requirements are fullfilled.








