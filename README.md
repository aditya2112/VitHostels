# VIT HOSTELS
  

VIT HOSTELS is a website where users can create and review hostels. In order to review or create a hostel, you must have an account. This project was part of our IWP course and was developed under prof Naveen Kumar N.

This project was created using Node.js, Express, MongoDB, and Bootstrap. Passport.js was used to handle authentication.  

## Features
* Users can create, edit, and remove HOSTELS
* Users can review hostels once, and edit or remove their review
* User profiles include more information on the user (full name, email, phone, join date), their hostels, and the option to edit their profile or delete their account
* Search hostels by name or location
* Sort hostels by highest rating, most reviewed, lowest price, or highest price

## Run it locally
1. Install [mongodb](https://www.mongodb.com/)
2. Create a cloudinary account to get an API key and secret code

```
git clone
npm install
```

Create a .env file (or just export manually in the terminal) in the root of the project and add the following:  

```
DATABASEURL='<url>'
API_KEY=''<key>
API_SECRET='<secret>'
```

Run ```mongod``` in another terminal and ```npm start``` in the terminal with the project.  

Then go to [localhost:8000](http://localhost:8000/).

To get google maps working check [this](https://github.com/nax3t/google-maps-api) out.
