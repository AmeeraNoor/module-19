Just Another Text Editor (J.A.T.E)
Description
J.A.T.E is a Progressive Web Application (PWA) that runs in the browser, offline and can be installed locally to your machine. This application features a number of data persistence techniques, insuring the application runs regardless of browser supported function. J.A.T.E uses an IndexedDB database and the idb package. This application is deployed to Heroku, to access it in production continue reading the documentation!

Table of Contents
Description
Table of Contents
Usage
Installation
License
Technologies Employed
Future Development
Contributing
Tests
Questions
Usage
User Story
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
Acceptance Criteria
GIVEN a text editor web application
WHEN I open my application in my editor
THEN I should see a client server folder structure
WHEN I run `npm run start` from the root directory
THEN I find that my application should start up the backend and serve the client
WHEN I run the text editor application from my terminal
THEN I find that my JavaScript files have been bundled using webpack
WHEN I run my webpack plugins
THEN I find that I have a generated HTML file, service worker, and a manifest file
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application
Installation
This application is deployed to Heroku.

To run J.A.T.E locally:

Pull down and/or branch this repository
Run npm i to install all dependencies
Invoke application with npm run start

The following animation demonstrates the application's functionality:
J A T E Demo


The following image shows the application's manifest.json file: manifest


The following image shows the application's registered service worker:
serviceworker


The following image shows the application's IndexedDB storage:
idb

License
This project is licensed under the MIT license.

A short and simple permissive license with conditions only requiring preservation of copyright and license notices. Licensed works, modifications, and larger works may be distributed under different terms and without source code.

For more information visit MIT Licensing.

Technologies Employed
Mini-CSS-Extract Plugin
Webpack+Workbox
Concurrently
JavaScript
IndexedDB
Express
NodeJS
Babel
Future Development
We would like to continue to add the following functionality to our application:

Overhaul CSS
Contributing
We'd love for you to contribute! In order to do so, fork this repository. Your pull request will need approval in order to merge to main.

Take a look at our Future Development section to see what we are looking to expand on (implemented features are denoted with a ✓). Feel free to implement your own ideas and merge request!

Tests
No tests were run to complete this CMS.
