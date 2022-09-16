# YelpCamp

YelpCamp is a website where users can create and review campgrounds. In order to review or create a campground, you must have an account. 

This project was created using Node.js, Express, MongoDB, and Bootstrap. Passport.js was used to handle authentication.  

## Features
* Users can create, edit, and remove campgrounds
* Users can review campgrounds once, and edit or remove their review
* Search campground by name or location

## Run it locally
1. Install [mongodb](https://www.mongodb.com/)
2. Create a cloudinary account to get an API key and secret code

```
git clone https://github.com/karthikraj15/Yelpcamp.git
cd YelpCamp
npm install
```

Create a .env file (or just export manually in the terminal) in the root of the project and add the following:  

```
API_KEY='<key>'
API_SECRET='<secret>'
```

Run ```mongod``` in another terminal and ```node app.js``` in the terminal with the project.  

Then go to [localhost:3000](http://localhost:3000/).


