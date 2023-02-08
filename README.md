# Flix
**Flix** is an app that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

![IMDB Clone](https://user-images.githubusercontent.com/89917595/217650891-e4f07a10-06f6-4352-92f1-5fdb6e49fc3e.png)


### User Stories

- [x] User can tap a cell to see more details about a particular movie.
- [x] User can tap a tab bar button to view a grid layout of Movie Posters using a CollectionView.
- [x] User sees an app icon on the home screen and a styled launch screen.
- [x] User can view and scroll through a list of movies now playing in theaters.
- [x] User can view the movie poster image for each movie.

### App Walkthrough GIF
<img src="http://g.recordit.co/uzqBi13SzP.gif" width="30%"> <img src="http://g.recordit.co/E0Nnv54l8m.gif" width="31%"><br>

### Notes
I got stuck when trying to execute `pod init`:
`zsh: /usr/local/bin/pod: bad interpreter: /System/Library/Frameworks/Ruby.framework/Versions/2.3/usr/bin: no such file or directory`<br>
I execute `gem install -n /usr/local/bin cocoapods`, it worked
