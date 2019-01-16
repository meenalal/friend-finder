# friend-finder

FRIEND FINDER APPLICATION

Description

Friend Finder implements friend matching based on the user's responses to a ten question survey. The user responds to questions with values from 1 (Strongly Disagree) to 5 (Strongly Agree). When the survey is submitted, an existing user record closet to the current user's response is found and returned. The closest set of user responses is defined as the set with the lowest absolute difference for all ten questioins combined.

Friend Finder application is meant to simulate dating app. The application is implemented using a Node.js and Express on the back end and the  Materialize CSS framework on the front end.

Demo

Friend Finder is deployed to Heroku.

Installation

To install the application follow the instructions below:

git clone git@github.com:meenalal/friend-finder.git
cd friend-finder
npm install

Running Locally

To run the application locally and access it in your browser, first set the PORT environmental variable to your choice.
An example is shown below.

export PORT=3000

After the PORT environment variable has been set, run the Node.js apllication with the command below.

node server.js

The application will now be running locally on PORT, in this case that is port 3030. You can then access it locally from your browser at the URL localhost:PORT, in this case localhost:3030.
