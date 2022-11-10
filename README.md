# Tripify

Tripify is a website where users can create and review campgrounds. In order to review or create a campground, you must have an account. 

This project was created using Node.js, Express, MongoDB, and Bootstrap. Passport.js was used to handle authentication.  

## Features
* Users can create, edit, and remove campgrounds
* Users can review campgrounds once, and edit or remove their review
* Search campground by name or location

## Run it locally
1. Install [mongodb](https://www.mongodb.com/) or use [MongoAtlas](https://www.mongodb.com/atlas/database)
2. Create a cloudinary account to get an API key and secret code

```
git clone https://github.com/karthikraj15/Tripify.git
cd Tripify
npm install
```

Create a .env file in the root of the project and add the following:  

```
CLOUDINARY_CLOUD_NAME='<name>'
CLOUDINARY_KEY='<key>'
CLOUDINARY_SECRET='<secret>'

MAPBOX_TOKEN='<token>'
```

Run ```mongod``` in another terminal and ```node app.js``` in the terminal with the project.  

Then go to [localhost:3000](http://localhost:3000/).


