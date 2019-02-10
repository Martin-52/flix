# Flix
Flix is an app that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

📝 `NOTE` Paste this template at the top of your existing `README.md` file from part 1 of this assignment. (🚫 Remove this paragraph after after checking off completed user stories)

## Flix Part 2

### User Stories

#### REQUIRED (10pts)
- [x] (5pts) User can tap a cell to see more details about a particular movie.
- [x] (5pts) User can tap a tab bar button to view a grid layout of Movie Posters using a CollectionView.

#### BONUS
- [X] (2pts) User can tap a poster in the collection view to see a detail screen of that movie.
- [ ] (2pts) In the detail view, when the user taps the poster, a new screen is presented modally where they can view the trailer.

### App Walkthough GIF
<img src="http://g.recordit.co/b6Vq5XBpA5.gif" width=250><br>
<img src="http://g.recordit.co/ef1Ib8ONJ1.gif" width=250><br>

### Notes
Keeping track of the outlets to which class was a little difficult to keep track of for me.

## Flix Part 1

### User Stories
`TODO://` In the **User Stories section below**, add an `x` in the `-[ ]` like this `- [x]` for any user story you complete. (🚫 Remove this paragraph after after checking off completed user stories)

#### REQUIRED (10pts)
- [x] (2pts) User sees an app icon on the home screen and a styled launch screen.
- [x] (5pts) User can view and scroll through a list of movies now playing in theaters.
- [x] (3pts) User can view the movie poster image for each movie.

#### BONUS
- [ ] (2pt) User can view the app on various device sizes and orientations.
- [ ] (1pt) Run your app on a real device.

### App Walkthough GIF
<img src='http://g.recordit.co/7HAGHOZVX3.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' /> <br>

### Notes
Describe any challenges encountered while building the app.

While making the custom MovieCell, I was unable to get the cell to display any of the data from the API. After reviewing my code, 
I realized the class and identifier name for the cell was different than the identifier I used to grab the cell in the MovieViewController
class.
