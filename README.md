Full Stack JS BoilerPlate
==========================

This boilerplate is designed to bring you as close as possible to actually writing your app immediately after install. It includes an Express server, a MongoDB Database and a client which uses Ember for a single page application. The architecture is REST and there is an example usage of CRUD and user authentication included. From there you're ready to code your app.

### Core components

+ Node - Server Side
+ Express - Web Server Framework
+ Ember - Client Side MVC Framework
+ MongoDB - Database

### Additional Tools Available
+ Bootstrap - front end framework
+ SASS - CSS pre-processor
+ jQuery - Write less, do more
+ Grunt - The Javascript task runner
+ Bower - Client-side dependency management
+ Handlebars - Advanced Client-side templating
+ Hogan - Server-side templating
+ Livereload - Automatic browser reload per save
+ Mongoose - A NodeJS object modeler for MongoDB
+ Passport - User Authentication
+ Mocha - Unit Testing
+ Font Awesome - CSS Icons


## Before You Begin 
Before you begin we recommend you read about the basic building blocks that assemble a Full Stack JS application: 
* MongoDB - Go through [MongoDB Official Website](http://mongodb.org/) and proceed to their [Official Manual](http://docs.mongodb.org/manual/), which should help you understand NoSQL and MongoDB better.
* Express - The best way to understand express is through its [Official Website](http://expressjs.com/), particularly [The Express Guide](http://expressjs.com/guide.html); you can also go through this [StackOverflow Thread](http://stackoverflow.com/questions/8144214/learning-express-for-node-js) for more resources.
* EmberJS - Ember's [Official Website](http://embers.com/) is a great starting point. You can also use [Ember Watch](http://www.emberwatch.com/)
* Node.js - Start by going through [Node.js Official Website](http://nodejs.org/) and this [StackOverflow Thread](http://stackoverflow.com/questions/2353818/how-do-i-get-started-with-node-js), which should get you going with the Node.js platform in no time.


## Prerequisites
Make sure you have installed all these prerequisites on your development machine.
* Node.js - [Download & Install Node.js](http://www.nodejs.org/download/) and the npm package manager, if you encounter any problems, you can also use this [Github Gist](https://gist.github.com/isaacs/579814) to install Node.js.
* MongoDB - [Download & Install MongoDB](http://www.mongodb.org/downloads), and make sure it's running on the default port (27017).
* Bower - You're going to use the [Bower Package Manager](http://bower.io/) to manage your front-end packages, in order to install it make sure you've installed Node.js and npm, then install bower globally using npm:

```
$ npm install -g bower
```

* Grunt - You're going to use the [Grunt Task Runner](http://gruntjs.com/) to automate your development process, in order to install it make sure you've installed Node.js and npm, then install grunt globally using npm:

```
$ sudo npm install -g grunt-cli
```

## Quick Install
Once you've installed all the prerequisites, you're just a few steps away from starting to develop your Full Stack JS application.

The first thing you should do is install the Node.js dependencies. The boilerplate comes pre-bundled with a package.json file that contains the list of modules you need to start your application, to learn more about the modules installed visit the NPM & Package.json section.

To install Node.js dependencies you're going to use npm again, in the application folder run this in the command-line:

```
$ npm install
```

This command does a few things:
* First it will install the dependencies needed for the application to run.
* If you're running in a development environment, it will then also install development dependencies needed for testing and running your application.
* Finally, when the install process is over, npm will initiate a bower install command to install all the front-end modules needed for the application

## Running Your Application
After the install process is over, you'll be able to run your application using Grunt, just run grunt default task:

```
$ grunt
```

Your application should run on the 3000 port so in your browser just go to [http://localhost:3000](http://localhost:3000)


### Acknowledgements
The Full Stack JS Boilerplate is created by [Martin Genev](http://www.twitter.com/mgenev) of [Gemini Connect](http://www.geminiconncet.com) and is largely based on the work of [Amos Haviv](https://twitter.com/amoshaviv) on [meanjs.org](http://www.meanjs.org) 
