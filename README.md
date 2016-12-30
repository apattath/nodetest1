This sample is taken from http://cwbuecheler.com/web/tutorials/2014/restful-web-app-node-express-mongodb/
It uses node.js, with mongoDB and jade templates to create an interactive single page web application. It uses Monk APIs to interact with the backend MongoDB Database.

For this project to run successfully,
1. MongoDB service has to be running on 27017 port (start service by using mongod)
2. app server has to be running (start server by running 'npm start' from project directory)
3. To access the app from the browser, browse to http://localhost:3000
4. Database can be found under data\ (for this project, you might need to populate database beforehand. The database name used is nodetest1. 
See line var db = monk('localhost:27017/nodetest1'); in app.js)
	- you can add stuff to the database manually using mongodb client. 
	- To access mongodb client, type mongo at the command prompt, then set current db to nodetest1, insert using mongodb commands.
	 
For future references:
1. client side stuff is under views\*, public\javascripts\*
2. Server side stuff (.\app.js, routes\users.js, routes\index.js)
