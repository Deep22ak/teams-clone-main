## Project- Teams Clone - Microsoft Engage 2021
This app is the teams clone built by Siddharth Gupta from NSUT, Delhi.
This is a video conferencing app in which you can chat with anyone.

## Hosted at https://siddharth-gupta-teams.netlify.app/
If you are ruuning the website for the first time then please be patient as heroku servers take time when activated for the first time
## Video at https://youtu.be/UHvFlqRzDaM

## Features
* Authentication via Google and Facebook
* Chat Rooms
* Video conferencing with real-time video and audio upto 50 users
* Enable/Disable camera
* Mute/unmute mic
* Screen sharing
* Live Closed Captioning
* Dominant Speaker indicator
* Network Quality Indicator
* Ability to add someone in the chat room during call
* Seen message bubbles
* Attachment option in chat
* Text styling in chat
* Audio input/output options before video call
* Max bit rate and presentation mode
* Render quality low/high/standard
* Dominant Speaker Mode Low/High/Standard
* Audio level button
* Responsive UI

## Browser Support
This application is supported only on Google Chrome.


Run the app locally with

    $ cd client
    $ npm install
    
In a parallel terminal run
    
    $ cd server
    $ npm install

As I have deployed the app on heroku, therefore to run it locally it is necessary to change .env file both in server and clinet
    REACT_APP_SYMBL_TOKEN_ENDPOINT=https://teamsclone-back.herokuapp.com/symbl-token
    REACT_APP_TWILIO_TOKEN_ENDPOINT=https://teamsclone-back.herokuapp.com/twilio-token
    
    Change these to
    REACT_APP_SYMBL_TOKEN_ENDPOINT=http://loaclhost:8081/symbl-token
    REACT_APP_TWILIO_TOKEN_ENDPOINT=http://localhost:8081/twilio-token
    
Now write

    $ npm run dev in client terminal
    $ npm start in server terminal
    
This will start the local token server and run the app in the development mode. Open [http://localhost:3000](http://localhost:3000) to see the application in the browser.

## Multiple Participants in a Room

If you want to see how the application behaves with multiple participants, you can simply open `localhost:3000` in multiple tabs in your browser and connect to the same room using different user names.

### Deployement

    The app is deployed in two ways
    1) The front end is deployed to netlify
    2) The back end is deployed to heroku
    
  To play with my deployed site, then this is the url
  https://siddharth-gupta-teams.netlify.app/
 
 If you running for the first time then please be patient while testing out the site as heroku servers takes some time while being activated for the first time
 
 ## Building of this app
 
 There are two folders: client and server
 
 Client is for front end - React.js
 
 Server is for backend - Node.js
 
 The app is using twilio SDK and symbl API for video connferencing functionality
 
 To break through the app
 
 Go to clinet and find Index.js
 Then find App.js
 You will they know all the components and routing
 
 ## Agile Methodology
![image](https://user-images.githubusercontent.com/72941353/125476376-ae33cbc2-2256-43a4-a446-ecffb7807327.png)
![image](https://user-images.githubusercontent.com/72941353/125473764-ae5bd4c5-fd70-40af-97b6-3c7f6b8a9dbf.png)
![image](https://user-images.githubusercontent.com/72941353/125473897-9d47ed45-2d59-4a40-8a52-2203fe443c58.png)
![image](https://user-images.githubusercontent.com/72941353/125473954-1c18419b-2c47-4848-a3a8-11c27cc13b9e.png)
![Screenshot (145)](https://user-images.githubusercontent.com/72941353/125477559-6ab65ec8-fa5f-46d7-beb9-39d1afc3a4f4.png)


## Workflow
If you want to look at my work flow
go to https://docs.google.com/document/d/1Gwq2wIEbA61vCsKedY-1Xy6djZT9HauQW9BEUEcZATM/edit?usp=sharing
