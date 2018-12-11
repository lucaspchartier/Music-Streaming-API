# Lucas' Music Streaming App (API)

# How it works

### Once the user signs in, the user can add, display, update, and remove artists of his or her choosing. Similar to Spotify and other similar music streaming apps, the user can build his or her library with a wide variety of artists and customize it to their liking.

# Links

* [Music Streaming Client](https://github.com/lucaspchartier/Music-Streaming-Client/)
* [Deployed Site](https://lucaspchartier.github.io/Music-Streaming-Client/)

# Entity Relationship Diagrams

* [Entity Relationship Diagrams](https://i.imgur.com/x1LTN0K.jpg)

# List of technologies used

* Ruby on Rails
* PostgreSQL

# Development process and problem-solving

### My main focus was to first get the API out of the way via Ruby on Rails and PostgreSQL. With rails creating the MVC for my user and artist tables, I could then make the artists a table under user so that a user can add artists to his or her queue. After completing the API and deploying it to Heroku, I then directed all my focus towards developing a client end that would appear user-friendly to the user. After getting my main framework set up, I connected my client to my API to test out the various features and ensuring that the adding, listing, updating, and removing of artists was fully functional without any outstanding bugs standing in the way. Whenever I did run into a bug, or came across a 400 error from my API, I would seek help either through the remote issue cues or through peers that may have ran into and overcame similar situations. After learning some hard lessons from my first project, Tic-Tac-Toe, I was more lenient and easy on myself, and took breaks to clear my mind, take some deep breaths, and reflect upon previous obstacles to overcome similar problems that I faced while developing this full stack application.

# Future versions

### While I primarily wanted to focus version 1 on a user adding artists to his or her cue, I also have future versions of this app already scoped out. In version 2, when a user selects an artist already added, I'm planning on having that artist's releases (albums, EPs, singles) listed. Moving onto version 3, whenever a user selects a release under a particular artist, I want every song to be listed under each release. Finally, in version 4, I want to implement a way for a user to add and create a playlist to his or her liking with a list of songs to fit a particular theme (fitness, going out, relaxation, etc.)