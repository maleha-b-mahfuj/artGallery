//Maleha Mahfuj

This is a dynamic real-time web application using the MERN (MongoDB, Express, React, Node.js) stack that allows artists to upload and exhibit their artwork. Patrons can securely sign up, like and follow artists.

To run my program, you need to have the respective modules downloaded:
npm install mongodb
npm install express
npm install pug. 
Then on the command line, please write ‘node server.js’ and go to your browser “http://localhost:3000/” and that will take you to the website.

Youtube video: https://youtu.be/Ep_qtZIwaU0

Database.initializer: populates my mongodb database with documents obtained from the gallery.JSON file.
server.js: handles all the requests made to the server.
views directory: contains all my pages.
Account.pug: holds the HTML for the main account page
Homepage.pug: holds the HTML for the sign in page
I created a page that holds all the work from the database. The html for that page:
allArtworks.pug
oneArtwork.pug holds the html for viewing one artwork piece.
oneArtist.pug holds the html for viewing the profile of one particular artist
Workshop.pug holds the html for adding a new workshop.
addArtwork.pug holds the html for adding a new artwork to the database
Search.pug holds the html that shows the results for when a search is made.

My public directory holds my client-side javascript files and my css folder.

I made a collection dedicated to “artworks”, “users” and “workshops” that artists create
from using my website. I displayed the reviews section in the profile page For my reviews, each review that the user made is shown as a link that directs them to the artwork to which the review is for.

I included a search bar in my header and each of my pages contains a header that has links that can redirect them back to the profile or the page that displays all the artworks.
Any art image that is shown links to their respective artwork page.
If you are an artist, you have to go back to the homepage before they can add a workshop or artwork. 
 
 
