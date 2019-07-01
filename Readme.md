## Docker examples for a full stack app with Node, Mongo and Vue

The content of the master branch is the final project, which will have:
* Back end: API to GET and POST contacts
* Mongo database: to store the contacts
* Front end: Vue app to list and add contacts, served from an NGINX

All three will run via docker-compose

### Branches
* basic-backend
A simple Node.js app build with Express.
The Dockerfile and docker-compose files are used to simply create and start the backend app.


* api-mongo
Adds new endpoints to the backend to GET and POST contacts and connects with MongoDB.
The docker-compose is updated to start two containers, the backend and the database.

### Work in progress....

