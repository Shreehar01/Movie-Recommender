# Movie-Recommender

Wondered how popular websites like Google and Netflix come up with movies that are similar to the ones you like?
It turns out that there are (mostly) three ways to build a recommendation engine:

* Popularity based recommendation engine
* Content based recommendation engine
* Collaborative filtering based recommendation engine
<hr>
But, what are the differences between the aforementioned recommendation systems? Lets explore:

#### Popularity based recommendation engine:
Perhaps, this is the simplest kind of recommendation engine that you will come across. The trending list you see in YouTube or Netflix is based on this algorithm. It keeps a track of view counts for each movie/video and then lists movies based on views in descending order(highest view count to lowest view count). Pretty simple but, effective. Right?
#### Content based recommendation engine:
This type of recommendation systems, takes in a movie that a user currently likes as input. Then it analyzes the contents (storyline, genre, cast, director etc.) of the movie to find out other movies which have similar content. Then it ranks similar movies according to their similarity scores and recommends the most relevant movies to the user.
#### Collaborative filtering based recommendation engine:
This algorithm at first tries to find similar users based on their activities and preferences (for example, both the users watch same type of movies or movies directed by the same director). Now, between these users(say, A and B) if user A has seen a movie that user B has not seen yet, then that movie gets recommended to user B and vice-versa. In other words, the recommendations get filtered based on the collaboration between similar user’s preferences (thus, the name “Collaborative Filtering”). One typical application of this algorithm can be seen in the Amazon e-commerce platform, where you get to see the “Customers who viewed this item also viewed” and “Customers who bought this item also bought” list.
<hr>

In this project, I have focused on building content-based and collaborative filtering-based recommendation engines. The results are surprising and the systems that I have built perform quite good. There are still a lot of improvements that can be done and this project can be further used to build an api so that the recommendations can be displayed in a web or a mobile application.  
