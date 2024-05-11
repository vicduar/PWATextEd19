Unit 19 Challenge

#Description:

Work on this project was implemented at the request of the client, whose user story stated the following: “AS A developer I WANT to create notes or code snippets with or without an internet connection SO THAT I can reliably retrieve them for later use.”

To satisfy the requirements of the client, I have been tasked to build a text editor that runs in the browser. The app will be a single-page application that meets the PWA criteria. Additionally, it will feature a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. The application will also function offline.

To build this text editor, I will start with an existing application and implement methods for getting and storing data to an IndexedDB database. I will use a package called `idb`, which is a lightweight wrapper around the IndexedDB API. It features a number of methods that are useful for storing and retrieving data, and is used by companies like Google and Mozilla.

##Acceptance Criteria:

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
WHEN I deploy to Render
THEN I should have proper build scripts for a webpack application

Github Repo Link:

https://github.com/vicduar/PWATextEd19.git

Render Link: 

https://pwatexted19.onrender.com

##Installation:

The project was created using VS Code editor where apollo client, react-bootstrap, graphql, react, at vitest were used to synthesize the framework, database, and libraries used. Once complete, the project was uploaded to a Github repository. Render was use to run the application.

##Usage:
The project was created and completed using VS Code. It was then loaded into Render, a web hosting solution used for hosting full-stack applications.

##Contributions:

Github (2024). A free web-service for storing and deploying websites. Multiple pages retrieved and utilized from www.github.com May 9, 2024.

Meyers, M. (2024, May 9). Tutoring session via Www.zoom.us . Denver University Bootcamp.

##License

This project is licensed under the MIT license.
