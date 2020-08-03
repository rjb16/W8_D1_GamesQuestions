What is responsible for defining the routes of the games resource?

The create_router.js creates the paths for each CRUD action

What do you notice about the folder structure? Whats the client responsible for? 

The client is responsible for the front end operations

Whats the server responsible for?

The server is hosting where the information is, and retrieving infro from
the mongodb database.

What are the the responsibilities of server.js?

The server.js is responsible for linking the databse to the client side/front end

What are the responsibilities of the gamesRouter?

gamesRouter is linking the gamesCollection from the database to the server


What process does the the client (front-end) use to communicate with the server?

not sure

What optional second argument does the fetch method take? And what is it used for 
in this application? Hint: See Using Fetch on the MDN docs

The doc says it can take an init options object as a second argument.

Which of the games API routes does the front-end application consume (i.e. make requests to)?

I think its /collections

What are we using the MongoDB Driver for?

Hosting the database, not sure