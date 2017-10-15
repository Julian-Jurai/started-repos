# Stared-Repos

This project was developed as a learning exercise. It was built using Node.js as an introduction to the  library.

## Learning Outcomes
-  Reading and Writing from Files
-  Creating and setting up a server
-  Gain familiarity with the http module, streams and event emitters
-  Fetching data from an external API from a POST request
-  Debugging using devtool


## About the project

The project involved receiving a username in the form of a POST request, then building the request body using the request object ReadableStream interface. The request body was then parse and the username was extracted which then was sent to Github's API to retrieve all that user's started repos. These were then written to a file via a write stream.
