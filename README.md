Pre Request:
============
  1. NodeJS
  2. npm
Modules:
 a. express           : npm install express
 b. request           : npm install request
 c. url               : npm install url
 d. q                 : npm install q
 e. node-base64-image : npm install node-base64-image
 
Execution:
==========
Compile the code using below command in console/terminal

  node main.js

Now Server get starts and listening on the port 8083(http://localhost:8083/)

Send the GET Request to the URL: http://localhost:8083/api/map with query parameters.

origin      : Name of starting location
destination : Name of starting location
image       : If you want map as image set image=1

Example: http://localhost:8083/api/map?origin=coimbatore&destination=selam&image=1