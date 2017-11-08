# Hackschool Final Project Spec

## BruinPlay

### What you’ll be making:

#### Overview:

You will be creating a SoundCloud-like web application that stores songs (MP3 files, song metadata, album artwork, etc.) in a database and presents these songs to a client (user). The client can also listen to any of the songs in the database, and can add or delete songs. This is your final project, so take it as a chance to apply everything that we’ve taught you this quarter!

#### First Steps:

##### Step 1: Fork the Repository

<img src="https://lh6.googleusercontent.com/qftHqJjw8ullF4sEGYoMKMnVDTmkB-lTz2lC5GEpnZfIwr6Ex2eD_yi5nn4QREFe-LR47IUpWiZSlTcYv-Uyc_H0odIYaQdKAwGXQKl112XoE7RkN_rho1DbGq7wCWA6H0cwUmSc" width="400px">

- Look for the "Fork" button on the top-right of the page, and click it.
- Select your profile.

##### Step 2: Download starter code

<img src="https://lh6.googleusercontent.com/pEVIvTfmqZDckInyeHxMb18PswSmEnYuzsufzaJoeTtCIL1ikgbHnRIAwN3HIA-41VmogbYOoDKlyJhAkN2qdtUUE0EAdy2D-qXjAy8mL_R2GmU10FNfNSVrMnN1D9Q90P1tOHYk" width="300px">

- Ensure that the BruinPlay repository is now under your own Github account.

Option 1 - Via Download

- Click on the green button at the top right corner of the page
- Click "Download ZIP"
- Open the starter folder in your preferred editor

Option 2 - Via Git

- Run the following in your terminal:

```
$ git clone https://github.com/[YOUR-GITHUB-USERNAME]/BruinPlay.git
$ cd BruinPlay
```

##### Step 3: Install libraries using NPM

- Run the following in your terminal (once you are in the BruinPlay directory):

```
$ npm install
```

- To start the server:

```
$ npm server.js
```

#### Essential Links:

- <a href="https://github.com/acm-hackschool-f17/Resources/blob/master/html-css-step-by-step.md">HTML/CSS step-by-step</a>
- <a href="https://github.com/acm-hackschool-f17/Resources/blob/master/Hack-Session-1-README.md">HTML/CSS Cheat Sheet</a>
- <a href="https://github.com/acm-hackschool-f17/Resources/blob/master/Learn-Session-2-README.md">Bootstrap/JavaScript Cheat Sheet</a>
- <a href="https://github.com/acm-hackschool-f17/Resources/blob/master/nodejs-handlebars-README.md">node.js and Handlebars.js Cheat Sheet</a>
- [TO-DO]\(MongoDB Cheat Sheet)

#### Functionalities Required for Certificate:

- Display all currently existing songs, along with their metadata (artist, title, album, album artwork, song length, genre, etc.).
- Add a new song (to server/database) and update website accordingly.
- Delete a song (from server/database) and update website accordingly.
- Play, pause, and seek audio player.
- Show an “Albums” view.

#### Additional Functionality:

- Show a history of songs that have been listened to.
- Filter by genre, artist, etc.
- Search for a song.

#### Example Apps:

- www.soundcloud.com
- www.spotify.com

#### What you’ll learn:

- How to independently develop a full-stack web application
- Front-end web development
  - Provide the structure for a dynamic web application using HTML
  - Style it using CSS
  - Use Handlebars.js for DOM manipulation to dynamically update your website
  - Use a JavaScript library to play audio
- Back-end web development
  - Create a server that can accept user input (add/delete songs) using node.js and JSON
  - Create a database using MongoDB

#### Tips:

- Brainstorm what views you’ll need and mock out what your application will look like before starting to build it.
- Focus on implementing core functionalities first before making things look nice.
- **Build incrementally. **
  - Start by getting the basic structure of the website (HTML/CSS) before beginning to work on the back-end.
  - Next, try to get the website to show all of the songs on the server.
  - Next, try to implement the audio playback functionality.
  - Finally, try to implement adding/deleting songs.
  - **Save your files often, and constantly test your website.** If you try to build too much at once, chances are your code will have a lot of bugs–and the more code you have, the harder it will be to find them.
  - Don’t be afraid to ask for help from your peers or mentors! We’re all here to help each other succeed. :)

