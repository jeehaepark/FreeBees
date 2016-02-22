# Freebees
Have something to give away? Here's Freebees.

[Freebees](https://freebees.herokuapp.com/)

## Introduction 

This web application allows a user to post items that she/he wants to give away. Other users can see the posted items and their locations.

## Getting Started

We used bower and npm to install dependencies. Nodemon runs the server, and Mongod runs the local database. The bower dependencies are downloaded to a node_modules folder, which is pre-specified in the .bowerrc file. Before running locally, run the following code in the command line.
```
bower install
npm install
mongod
nodemon index.js
```

Note: To use mongod, you must set the database path. You can do so with the following command.
```
mongod --dbpath <path>
```
## Tests

We have a test inside our specs folder.


## File Structure

Files are organized in the following directories: Client, Server.

## Choice of Technologies

For this project, we used AngularJS for our front end and Node.js, Express, and MongoDB for our server and database.

We used MongoDB for the document storage of the item names and the item locations. We used an ORM called mongoose, which is an npm module, which gives us easier access to our database. Refer to this link to learn more about mongoose [Mongoose Doc](http://mongoosejs.com/). We used MongoLab as a heroku addon when delpoying our app.

## Google Maps API

We used Google Maps JavaScript API for our locations.[Google Maps JavaScript API](https://developers.google.com/maps/documentation/javascript/)

## Features

- Users can add one item at a time with its physical address as location.
- Users can remove an item from the map  when it becomes unavailable.
- Users can use their location based on IP address.

## In progress

- Filter based on when item was submitted.

## Git Workflow

Please refer to the `_CONTRIBUTING.md `file to see our git workflow.

## Style Guide

Please refer to the `_STYLE-GUIDE.md `file to see our style guide.

## Contributors
- Collin Adams ([Collin Adams](https://www.linkedin.com/in/collin-adams-99018788?trk=nav_responsive_tab_profile))
- Alice Kao ([Alice Kao](https://www.linkedin.com/in/alice-kao-94768910?authType=NAME_SEARCH&authToken=wwuT&locale=en_US&trk=tyah&trkInfo=clickedVertical%3Amynetwork%2CclickedEntityId%3A37507591%2CauthType%3ANAME_SEARCH%2Cidx%3A1-1-1%2CtarId%3A1455832165532%2Ctas%3Aalice%20ka))
- Jessica Park ([Jessica Park](https://github.com/tinkleJess))
- Michael Serna ([Michael Serna](https://www.linkedin.com/in/michael-a-serna-9a899727?trk=send_invitation_success_message_name&goback=%2Enpv_AAkAAAWpqdABlWdGVJOytmG*4DUiPSbSqm9ULBsg_*1_*1_NAME*4SEARCH_LCwI_*1_en*4US_*1_*1_*1_*1_*1_*1_*1_*1_*1_*1_*1_*1_*1_*1_*1_*1_*1_*1_*1_*1_*1_*1_*1_*1_*1_*1_*1_*1_*1_tyah_*1_*1))


MKS Greenfield Project