## Things to do in VJ Rustic MVC
-------------------------------
### Structure 
* Routes
* Response
* Request
* Headers
* Controllers
* Models
* Templates
-----------
#### Routes
Routes structure will contain all the routes the request can go to. 
It will include the type of request is such as GET, POST,Put, DElete. 
It will contain all the headers from the request, 
and also store it for the developer to use.
It will store the Request for the use to use within the Controller,
These Request will store all the variables and their values in the datatype.
-----------
#### Response
This is more of a return value that the server will send back to the client
It will contain all the values wanted to be send back, such as the json body, 
It will also include the response type such as (200,300, 401,500,etc).
Also at the end it will contain all the headers which are required by the user
-----------
#### Request
Request stores all the variables sent by the client to the server to be used by it. 
These variables will be sorted according to its datatype, and be automatically assigned. 
-----------
#### Header
Header is the structure where all the header values are recieved from the client. 
This is also a value that the controller recieved from the route. 
------------------------------------------------------------------

#### Controller
Controller is a structure where 