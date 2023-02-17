This is a basic implementation of a proxy server using the Express.js library 
and the http-proxy-middleware package.

The Author is 
https://dev.to/decker67/write-your-own-cors-proxy-with-nodejs-in-no-time-30f9

The proxy server will listen on port 8088 and proxy requests to the specified URL, 
which is obtained from the request path.

how to run this code:

# `npm install`
# `node server.js`

If everything works correctly, the console will display a message saying that 
the proxy server is running on port 8088

Now you can make requests to http://localhost:8088/https://example.com/login 
to proxy the request to the specified URL