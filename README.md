
On client startup.

* Client does a GET to /init in order to obtain the configuration block. 


Client makes a POST to the server every x minutes set it's location data.

* Make a request to http://ip-api.com/json to get location data.
* POST response from http://ip-api.com/json up to the server.
* Server may respond with a config block which the client should then handle.
