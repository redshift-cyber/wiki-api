# wiki-api
This is a very simple RESTful API made using javascript, mongodb and mongoose. If you are facing any problems with this api you can make an issue on github.

# How to get started with the api:

****you need to have node js, mongodb and git installed****

git clone the project:
```
git clone https://github.com/iron-coder12/wiki-api.git
```

Install all the dependencies:

```
node install
```

Now all the dependencies are installed the next step is to get the mongo db server running.

open a new terminal window (or if you are using hyper terminal ****hyper.is**** you can open a new tab) and enter this commman:

```
mongod
```

the next step is you must have a API client (through which we will send GET requests and POST requests). You can use postman's api which you can get from https://www.postman.com/ 
For now I am going to be using thunder client (you can get thunder client by installing the ****thunder clien**** vs code extension).

now that you have opened your api client in your terminal start the app using 
```
node app.js
```

****Make sure you do not quit the mongo db server or your app will not run****

open up your Api client and make a post request. then go to body and chose form-encoded(it could be xxx-form-encoded in postman). Then enter the title and the content and hit send. you should see something like this:

***this is an important step as you just cloned the project there are no articles in the database right now****

<img src="https://github.com/iron-coder12/wiki-api/blob/master/Capture.PNG?raw=true">

now if you will switch back to the GET request you will see your article show up:


