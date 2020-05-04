# React Chat App

Real-time chat app built with React, Express, Node.js, Socket.IO

## Getting Started

Running client:

```
cd client
npm start
```

Running server:

```
cd server
npm start
```

## Deployment

### Netlify (Client)

Change current directory to client:

```
cd client
```

Install netlify CLI and login to netlify:

```
netlify login
```

### Build the client

```
npm run build
```

#### Deploy your changes

Deploy build folder to netlify and click on the generated `Website Draft URL` to access the app.

```
netlify deploy
```

### Heroku (Server)

Change current directory to server:

```
cd server
```

Download and install the Heroku CLI. Log in to your Heroku account and follow the prompts to create a new SSH public key.

```
$ heroku login
```

#### Clone the repository

Use Git to clone `YOUR-APP-NAME`'s source code to your local machine. Replace `YOUR-APP-NAME` accordingly to your own app's name on Heroku.

```
$ heroku git:clone -a YOUR-APP-NAME
$ cd YOUR-APP-NAME
```

#### Deploy your changes

Make some changes to the code you just cloned and deploy them to Heroku using Git.

```
$ git add .
$ git commit -am "make it better"
$ git push heroku master
```
