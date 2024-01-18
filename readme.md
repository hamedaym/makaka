Running BBCloneMail On Your Computer
BBCloneMail is a NodeJS app built on Express.js. To run it on your computer you'll want to clone this repository to your machine somewhere, and then follow these steps:

Install the latest http://nodejs.org if you don't have it already
Open a command prompt / terminal window in the BBCloneMail project folder
Run npm install to install all of the needed components
Run npm start to start the server
Open http://localhost:3000 in your browser
Note that step 1 through 3 only have to be done once. After you have done that, you just need to run step 4 and 5 any time you want to see the app running on your computer.

A Work In Progress
Keep in mind that this is always a work in progress. While the source code and functionality do demonstrate all of the core features and capabilities of Backbone.Marionette, the application itself is very limited in it's functionality.

Also note that I haven't optimized the JavaScript downloads in any way. There is no minification, and no asset packaging to create a single download for the entire application at this point. As a result, the app takes a moment or two to download all of the JavaScript files and start up.

As I continue working on functionality, I'll also put in some optimizations for the JavaScript, so that it starts up faster.
