# Music Database API

### How it works
Once the user signs in, the user can add, display, update, and remove artists of his or her choosing. The user can build his or her library with a wide variety of artists and customize it to their liking.

### Links
* [Music Database Client](https://github.com/lucaspchartier/Music-Database-Client/)
* [Deployed Heroku](https://salty-wave-91914.herokuapp.com/)
* [Deployed Client](https://lucaspchartier.github.io/Music-Database-Client/)

### Entity Relationship Diagrams
![Entity Relationship Diagrams](https://i.imgur.com/x1LTN0K.jpg)

### API Routes and Paths
| Verb   | URI Pattern            | Controller#Action |
|--------|------------------------|-------------------|
| POST   | `/sign-up`             | `users#signup`    |
| POST   | `/sign-in`             | `users#signin`    |
| DELETE | `/sign-out`            | `users#signout`   |
| PATCH  | `/change-password`     | `users#changepw`  |
| POST   | `/artists`             | `artists#create`  |
| GET    | `/artists`             | `artists#index`   |
| GET    | `/artists/:id`         | `artists#show`    |
| PATCH  | `/artists/:id`         | `artists#update`  |
| DELETE | `/artists/:id`         | `artists#delete`  |

### List of technologies used
* Ruby on Rails
* PostgreSQL

### Future versions
While I primarily wanted to focus version 1 on a user adding artists to his or her cue, I also have future versions of this app already scoped out. In version 2, when a user selects an artist already added, I'm planning on having that artist's releases (albums, EPs, singles) listed. Moving onto version 3, whenever a user selects a release under a particular artist, I want every song to be listed under each release. Finally, in version 4, I want to implement a way for a user to add and create a playlist to his or her liking with a list of songs to fit a particular theme (fitness, going out, relaxation, etc.) In addition, I defintely want to revamp and overhaul my CSS and styling, mainly because my main focus was to get the app to work as well as meeting all requirements for the project itself. I based the CSS and styling loosely off of Spotify, since I use that app a lot when I workout, relax, and commute every day.

### Planning, process and problem-solving strategies
My main focus was to first get the API out of the way via Ruby on Rails and PostgreSQL. With rails creating the MVC for my user and artist tables, I could then make the artists a table under user so that a user can add artists to his or her queue. After completing the API and deploying it to Heroku, I then directed all my focus towards developing a client end that would appear user-friendly to the user. After getting my main framework set up, I connected my client to my API to test out the various features and ensuring that the adding, listing, updating, and removing of artists was fully functional without any outstanding bugs standing in the way. Whenever I did run into a bug, or came across a 400 error from my API, I would seek help either through the remote issue cues or through peers that may have ran into and overcame similar situations. After learning some hard lessons from my first project, Tic-Tac-Toe, I was more lenient and easy on myself, and took breaks to clear my mind, take some deep breaths, and reflect upon previous obstacles to overcome similar problems that I faced while developing this full stack application.
