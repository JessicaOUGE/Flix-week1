
# Flix

Flix is an app that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

## Flix Part 2

### User Stories

#### REQUIRED (10pts)
- [X] (5pts) User can tap a cell to see more details about a particular movie.
- [X] (5pts) User can tap a tab bar button to view a grid layout of Movie Posters using a CollectionView.

#### BONUS
- [ ] (2pts) User can tap a poster in the collection view to see a detail screen of that movie.
- [ ] (2pts) In the detail view, when the user taps the poster, a new screen is presented modally where they can view the trailer.

### App Walkthough GIF

<img src="http://g.recordit.co/usG93q0pEx.gif" width=250><br>

### Notes
1. When I add heros image, and code at Class MovieGridViewController.swift. It shew me an error that can't find as_setImage.
Then I reviewed the last 3 videos and did it again, the error disappeared.
2. It's difficult to figure out the Superhero's image's size.

## Flix Part 1

### User Stories

#### REQUIRED (10pts)
- [X] (2pts) User sees an app icon on the home screen and a styled launch screen.
- [X] (5pts) User can view and scroll through a list of movies now playing in theaters.
- [X] (3pts) User can view the movie poster image for each movie.

#### BONUS
- [X] (2pt) User can view the app on various device sizes and orientations.
- [X] (1pt) Run your app on a real device.

### App Walkthough GIF

<img src="http://g.recordit.co/7qaDNkimtG.gif" width=250> <img src="http://g.recordit.co/vQ1YkuybNu.gif" width=250><br>

### Notes
"Thread 1: signal SIGABRT", When I try to run this app on my iphone.
And ERROR:
/private/var/containers/Bundle/Application/8C0DD525-AACE-4FFC-B97C-A3273A04229F/Flix-week1.app/Frameworks/Alamofire.framework/Alamofire: stat() failed with errno=1 /private/var/containers/Bundle/Application/8C0DD525-AACE-4FFC-B97C-A3273A04229F/Flix-week1.app/Frameworks/Alamofire.framework/Alamofire: code signature invalid for '/private/var/containers/Bundle/Application/8C0DD525-AACE-4FFC-B97C-A3273A04229F/Flix-week1.app/Frameworks/Alamofire.framework/Alamofire'
/private/var/containers/Bundle/Application/8C0DD525-AACE-4FFC-B97C-A3273A04229F/Flix-week1.app/Frameworks/Alamofire.framework/Alamofire: stat() failed with errno=1

Finally, I have connected to IOS 12, and it works! And there some changes for version 12. I should add "@available(iOS 13.0, *)" at AppDelegate.swift and SceneDelegate.swift. Also add "var window: UIWindow?" at AppDelegate.swift and SceneDelegate.swift. 

