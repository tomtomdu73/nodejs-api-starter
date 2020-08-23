# NodeJS API Starter

A simple and light NodeJS/Express API starter including a Docker image.

## Getting Started

### Prerequisites

If you are not mounting the Docker image, make sure you have **nodemon** package installed.

You also need to [create a free account with MongoDB Atlas](https://www.mongodb.com/cloud/atlas) since we are using the cloud version of MongoDB.

### Installing

First in *app.js*, edit this line with your own credentials and database name :

```
mongodb+srv://<username>:<password>@cluster0.uqirs.mongodb.net/<dbname>?retryWrites=true&w=majority'
```

Then, just run the following command in the root folder. 

```
npm start
```

You can now query your API on *http://localhost:3080*

## Features

### Pre-Built endpoints

- **/user** : Secure Sign In + Sign Up
- **/stuff** : CRUD functions ready for your own model

### Packages installed

* [Express](https://expressjs.com/)
* [Mongoose](https://www.mongodb.com/)
* bcrypt
* body-parser
* multer


## Authors

* **Will ALEXANDER** - *Initial work* - [Openclassroom](https://openclassrooms.com/fr/courses/6390246-passez-au-full-stack-avec-node-js-express-et-mongodb/6466277-creez-une-application-express)
* **Thomas COSIALLS** - *Wrapping up things together*


