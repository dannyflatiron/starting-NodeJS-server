# starting-NodeJS-server

10/21/20

-NodeJS is a javascript runtime. It is mostly used to create a server but it can also be used as a separate javascript "engine"

-NodeJS server runs as an event loop meaning it runs forever and is meant to run with non-blocking code or otherwise known as synchronus code that could severly impact performance

-how to handle requests from the server and read data from the requests through available methods and variables such as 'request.url', 'request.headers' etc

-learned how to set response headers with 'response.setHeader(). An error will show up if 'response.write()' is used after 'response.end()'

-how to setup a route with 'const url = request.url

-how to setup a redirect after submitting a form

-understand the benefits of asynchronus code in NodeJS and what problems may arise from it if used improperly

-NodeJS uses only one thread in an operating system, it handles multiple requests by reading all the callback functions in the event loop and sends the heavy work such as file uploads to a worker pool that is managed by NodeJS ande exists outside of your codebase and runs on different threads 

-utilize the Node Module System

-setting up an npm script

-learned how to automatically update server after code changes with nodemon 

-learned how to utilized debugging vs code feature in tandem with nodemon as a global package on my computer

-differntiate installing 3rd party packages between production dependencies, development dependencies and global dependencies 

-learning what is express.js (it is middleware) and installing it

-when using Express use next() to allow the program to travel from one middleware to the next middleware. middleware is defined when .use(request, response, next) is utilized 

-aware of need to order middlewares to prevent response.send errors 

-learned how to parse incoming request data with the body-parser package

-how to manage routing 

-learned how to filter routes

-advanced css styling

-how to submit files statically

-how to use the path module to get absolute clean paths which would work on every operating system