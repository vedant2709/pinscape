/ - login and register screen ✅
/register ✅
/login ✅

/profile - profile page with boards
/feed - feed page with all different pins
/save/:pinid - will save pin to a board
/delete/:pinid - will delete a pin from board

/logout
/edit
/upload

packages required for this project:-
mongoose 
passport 
passport-local 
passport-local-mongoose 
express-session

steps:-

1) create Login and Register page and also create their corresponding routes.
2) create db by connecting to mongoose
3) create a schema which contains : username, name, password,email, profileImage, contact and no. of boards as fields.
4) create a model which will contain all of the above mentioned data of an user and also export the model using "module.exports" so that you can use it in another file.
5) Now follow the steps and write code for express sessions and passport initialization. 
6) Make a post route which will take all the data from form and store it in a variable
7) Authenticate user based on "local" strategy and redirect the user to profile page.
8) Make another route for login in which you are supposed to mention two things that are on success which route should be redirected and on failure which route should be redirected.
9) Create a route for logout and make sure that after being logged out user must be redirected to home route or "/" 
10) create one protected route and add it to profile router. This will make sure that no one can redirect to profile page without being authenticated.
11) Now its time to design profile page in which we will be showing user data and also feeds. Here we will also give username to change its profile picture.
12) For uploading files we will be using multer . Multer is a node.js middleware for handling multipart/form-data, which is primarily used for uploading files.


