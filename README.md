# Flix

Flix is an app that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

## Flix Part 2

### User Stories

#### REQUIRED (10pts)
- [x] (5pts) User can tap a cell to see more details about a particular movie.
- [x] (5pts) User can tap a tab bar button to view a grid layout of Movie Posters using a CollectionView.

#### BONUS
- [x] (2pts) User can tap a poster in the collection view to see a detail screen of that movie.
- [ ] (2pts) In the detail view, when the user taps the poster, a new screen is presented modally where they can view the trailer.

### App Walkthrough GIF

![](https://i.imgur.com/XfgKa6l.gif)

### Notes
One of the main challenges that I ran into with this app was an error that rose when I had to implement "posterView.af.setImage(withURL: posterUrl!)" again in my MovieGridViewController file. An error arose stating that "value of type 'UIView' has no member 'af'", yet I had imported AlamofireImage. Upon further investigation, the issue lied in my posterview connection, as it did not connect as a UIImageView. Once I deleted the previous connection and redid it, the app worked fine.

Also, in attempting the bonus of adding a collection view for details, it was interesting trying to figure out how to adapt it from the table view one we created previously. It was definitely a fun challenge for me!

---

## Flix Part 1

### User Stories

#### REQUIRED (10pts)
- [x] (2pts) User sees an app icon on the home screen and a styled launch screen.
- [x] (5pts) User can view and scroll through a list of movies now playing in theaters.
- [x] (3pts) User can view the movie poster image for each movie.

#### BONUS
- [ ] (2pt) User can view the app on various device sizes and orientations.
- [ ] (1pt) Run your app on a real device.

### App Walkthrough GIF

![](https://i.imgur.com/f8yYQxz.gif)

### Notes
Describe any challenges encountered while building the app.

As far as challenges, just learning about the different controllers and storyboards and making sure everything connected properly was the main thing that I needed to focus hard on.

Along with this, working with the phone simulator is an adjustment too. Sometimes new changes that I had added wouldn't load (for instance, my loading screen picture did not work), but once I closed out the simulator and reloaded it, everything worked fine. 

It was cool to use and display an API on a mobile setting, and I'm looking forward to getting to learn more.
