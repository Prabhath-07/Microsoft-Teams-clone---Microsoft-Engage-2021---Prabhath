# Microsoft-Teams-clone---Microsoft-Engage-2021---Prabhath
## To use the application
### Local Setup
1. Clone this repository or download it to your system.
2. In .env folder put your Mongo URL, for more information refer this [Documentation](https://docs.atlas.mongodb.com/tutorial/create-new-cluster/).
3. In CLI type the following commands:<br>
    npm install<br>
    npm start
4. Open localhost 3000 in your browser.

### Deployed link
I have deployed the project on heroku. Here is the [link](https://ms-teams.herokuapp.com/).

## Video Demo 
This is the link to video demo: [DEMO](https://drive.google.com/file/d/1IxMbyC3DGRxHXh59aU-n_ZEEJHDpz7ZK/view?usp=sharing)

## Problem Statement
To build a fully functional prototype with at least one mandatory functionality - a minimum of two participants should be able to connect using the product to have a video conversation.

### Adopt Feature
Include a chat feature in your application where meeting participants can share info without disrupting the flow of the meeting. Through this feature, the participants should be able to have a conversation before joining, while in the meet, and after leaving the meeting.

## Features built 
1. Multiple users can join the meeting. (**WebRTC** can allow a million users.)
2. Video and Audio options
3. Chat
4. Send Invite option
5. Share screen
6. Recording
7. Change camera (only shown on mobiles)
8. Pin button to focus only on a single user
9. Show number of participants
10. Display Time
11. Leave/Join Meeting

## Agile Methodology and Approach to Build the Project
Agile Methodology was taught to us in Webinars conducted as a part of the program. Agile Scrum Methodology is a project management method that is best used to improve the project in every iteration. Each iteration has sprints, where the goal in each sprint is to build the most important feature first and then improve the project as a potentially deliverable product. Microsoft has provided us with sprints: Design, Build, Adopt which are 1-2 weeks each.
I have sub-divided these sprints into many other short sprints which I followed to complete the product. They are:
1. Exploring all the libraries and packages which can be used.
2. Setting up the database and design sign-in and sign-up pages.
3. Creating a home page for the user.
4. Setting up the Meeting interface by giving each room a unique id.
5. Building audio, video, and Leave Meeting features.
6. Building screen share and pin option to focus only on one user.
7. Adding Recording and Change Camera features to the Meeting.
8. Building Chat application.
9. Adding time, invite button, and number of participants to the meeting room.
10. Deploying product on heroku.

## Libraries and Dependencies used
1. cookie-session
2. dotenv
3. ejs
4. express
5. express-ejs-layouts
6. express-flash
7. mongoose
8. passport
9. passport-local
10. peer
11. peerjs
12. socket.io
13. uuid

These are found in package.json as well.

## Contact
For any queries and suggestions.<br>
Email: mallavarapusp@gmail.com

