Registration Form Project 



Overview
This project is a simple registration form built with Node.js, Express, and MongoDB. It allows users to register with their name, email, and password.
The backend server handles form submissions and stores user data in a MongoDB database.




registration-form/
│
├── server.js
├── package.json
├── .env
├── views/
│   └── index.html
└── models/
    └── User.js

    


Files


server.js: Main server file for setting up the Express server and handling routes.


package.json: Contains project metadata and dependencies.


.env: Stores environment variables such as MongoDB URI and port number.


views/index.html: Frontend HTML form for user registration.


models/User.js: Mongoose schema for user data.





Clone the Repository


git clone <repository_url>
cd registration-form

 Install Dependencies
 npm install

 
Configure Environment Variables
MONGO_URI=mongodb://localhost:27017/registration_form
PORT=3000


Start MongoDB
Ensure that MongoDB is running on your local machine or remote server.

Start the Server
node server.js

