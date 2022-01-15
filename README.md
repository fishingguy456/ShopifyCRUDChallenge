# ShopifyCRUDChallenge
This was made for Shopify's Backend Developer/Production Engineer Intern Challenge. This inventory tracking app was built using the MERN Stack (MongoDB, Express, React, Node). The selected additional feature was: Push a button export product data to a CSV

## Instructions to use this webapp:

Install Node and Git onto your computer:

https://nodejs.org/en/download/

https://git-scm.com/downloads

Make sure they are working by running `git` and `node`. They are working if no errors are returned

Clone this repository to your local machine:

`git clone https://github.com/fishingguy456/ShopifyCRUDChallenge.git`

Enter the client folder through a command line or terminal:

`cd client`

Install React and Axios:

`npm i react axios`

Exit the client folder:

`cd ..`

Enter the server folder:

`cd server`

Install Express, Cors, Mongoose, (Optionally: Nodemon)

`npm i express cors mongoose nodemon`

Make sure that there is nothing currently running on localhost:3001

In the server folder (which you should currently be in), run the server with:

`node index.js`

Open a new instance of your terminal and enter the client folder (`cd client`). The app will not work properly if the server has not launched yet.

Launch the App:

`npm start`

The app is now running on localhost:3000! Create items at the top; read, update and delete them in the middle; and download them to a CSV file at the bottom.
