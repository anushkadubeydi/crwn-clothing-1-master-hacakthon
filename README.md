# crwn-clothing-1-master-hacakthon
Description
Before we move forward take a look at the website, register yourself with it and try and play around with things.  

"Crown Clothing" Crown Clothing Ltd. is an E-commerce Website where you can go and shop for clothing.

Technology Used
JavaScript, React, Redux, Redux-Saga, React Hooks, Express.js, Node.js, Material UI, HTML5, CSS3, Firebase, SCSS, Styled-Components, Git
JavaScript as the base developement language.
Server was built using Nodejs and Express.
Database was set using Firebase/ Firestore.
Redux used for state managemnet.
Stripe API used for payments.
SCSS used for styling the components.
Styled Components used in some components to style the application.
React Hooks used in the front-end to avoid using stateful components.
Jest used for Unit Testing.
Heroku was used to deploy the application.
Installation Guide
Steps to run in development mode
Fork the repo and clone it.
Make sure you have npm and Node.js installed in your system.
Check the libraries and packages needed from package.json file under the dependencies object.
In the terminal type npm install to install the packaged of the application.
Setup your Firebase account.
Setup your Stripe API account.
Open src/components/stripe-button/StripeCheckoutButton.js and replace the publishable key with your stripe publishable key.
Create .env file in src and put it in .gitignore. Now put your stripe screte key in .env file by creating a STRIPE_SECRET_KEY variable.
Run npm run dev to run server or and client side at the same time.
