# video-con-app 💻

![Video Con App](https://user-images.githubusercontent.com/44089458/127033826-f648843f-467a-4167-8c8e-12f01e58aaf5.png)

Video Con is a 1:1 real-time video conference application which you can use to have a video call with your family, friends or with anyone whom you send the link of the video conference. 

## Features 
- 1:1 single page video streaming. 
- Login details required.
- Video conference possible only when one user shares their "ID" with the other user.
- Call and Hang up anytime you want. 

## Setup Instructions 
1. Initializing Frontend
```bash
$ cd client 
$ npm i 
$ npm start
```
The above commands runs the application at localhost:3000

2. Initializing Backend 
```bash
npm i
node index.js

# for the developer mode use the following 
nodemon index.js
```
The above command(s) runs the application at localhost:5000

## Deployment 
The server of this application has been deployed on Heroku while the frontend is deployed on Netlify. Click [here]() to view the application.

## How to use the Application 
### STEP 1: Visit the [website](https://video-con-ap.netlify.app/) and click on the "Allow" button. 
<img width="239" alt="allow" src="https://user-images.githubusercontent.com/44089458/127039204-02029ce6-c81c-4e65-b4ec-1755cfd76ce0.png">

### STEP 2: Enter your name and click on the "COPY YOUR ID" button. Send the copied link to the user you want to have a video call with. 
![image](https://user-images.githubusercontent.com/44089458/127040738-d9287982-a687-42eb-a8ac-598bb3c1864d.png)

NOTE: Once you enter your name you can view it on the top of your streaming video like the one given below. 
![image](https://user-images.githubusercontent.com/44089458/127041405-2e04b782-47b1-405a-8a9f-95cce8a1a484.png)


### STEP 3: Once you get the notification of your friend calling you, you may accept or decline it. After accepting, your video will stream beside your friend's video.
![image](https://user-images.githubusercontent.com/44089458/127041814-9e5f3a6b-02ee-48e7-a49f-caff77e338bb.png)

### STEP 4: You may end the call by clicking on "Hang up" button given just below streaming video. 
![image](https://user-images.githubusercontent.com/44089458/127041848-c40e4257-bb70-467b-9649-ded7ebfd7a89.png)


## Packages/Tools Used 
- [create-react-app](https://github.com/facebook/create-react-app)
- [React Router Dom](https://www.npmjs.com/package/react-router-dom)
- [express](https://expressjs.com/)
- [socket.io](https://socket.io/get-started/chat)
- [cors](https://www.npmjs.com/package/cors)
- [Copy tp Clipboard](https://www.npmjs.com/package/react-copy-to-clipboard)
- [Peer JS](https://www.npmjs.com/package/peerjs)
- [material-ui](https://material-ui.com/)
- [Heroku](https://www.heroku.com/)
- [Netlify](https://www.netlify.com/)
