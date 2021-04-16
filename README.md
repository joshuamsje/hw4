# hw4
# Flix
Flix is an app that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

---

## Flix
#### REQUIRED (10pts)
- [x] (70pts) User can view a list of movies (title, poster image, and overview) currently playing in theaters from the Movie Database API.
- [x] (10pts) Views should be responsive for both landscape/portrait mode.
   - [x] (5pt) In portrait mode, the poster image, title, and movie overview is shown.
   - [x] (5pt) In landscape mode, the rotated alternate layout should use the backdrop image instead and show the title and movie overview to the right of it.
- [x] (20pts) Improved the user interface by experimenting with styling and coloring.

### App Walkthough GIF

<blockquote class="imgur-embed-pub" lang="en" data-id="gk0NA44"><a href="https://imgur.com/gk0NA44">View post on imgur.com</a></blockquote>

### Notes
I encountered a with UI/UX design issues when building the app. Coming up with creative ways to improve the UX design and make it pop to a user was hard to think about. Then, 
I realized I could set the border on the recycler view so I could get rid of the boring black background. 


### Open-source libraries used

- [Android Async HTTP](https://github.com/codepath/CPAsyncHttpClient) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Androids
