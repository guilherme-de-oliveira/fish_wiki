# fish_wiki
 Redis Implementation.

 This is an application that fetches data from an API and returns the data as a response to the client. You then modified the app to cache the API response in Redis on the initial visit and serve the data from the cache for all subsequent requests. You modified that cache duration to expire after a certain amount of time has passed, and then you used middleware to handle the cache data retrieval.

 To run it, we have first to start the Redis server with command: redis-server.
 Then we're able to start the server on: node server.js
