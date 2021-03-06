# PERN project for CS 204
* This is a quiz application with user authentification

<img src="https://github.com/Zhantoroev/awesome-react-app/blob/main/public/img1.png" width="49%" /> <img src="https://github.com/Zhantoroev/awesome-react-app/blob/main/public/img2.png" width="49%" />
<img src="https://github.com/Zhantoroev/awesome-react-app/blob/main/public/img3.gif" width="100%" />

## [API Description](https://peaceful-retreat-54716.herokuapp.com/api-docs/)
* To view all users data from database `/all`  HTTP Method: Get
* To view a certain user data from database `/all:id`  HTTP Method: Get
* To sign in `/signin` HTTP Method: Post
* To register `/register` HTTP Method: Post
* To view an authorized user's (your) data `/profile/:id` HTTP Method: Get/Post
* To view and update score `/score` HTTP Method: Put


## Tool / technologies used
* `PERN Stack` (Postgeres Express React Node)
* `bcrypt` for hashing password
* `knex-js` to connect database with the backend
* `particles-js` for background
* `tachyons` for styling
* `REST API`


### To run the project:
1. Clone this repo
2. Run `npm install`
3. Run `npm start`

[Server](https://peaceful-retreat-54716.herokuapp.com/)\
[Live](https://awesome-react-app.herokuapp.com/) on Heroku