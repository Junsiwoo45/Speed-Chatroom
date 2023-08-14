# Speed Card Game/Chatroom
-	Creates a functioning chatroom that displays the messages in real time using sockets.
-	Having security login and register features
-	Connecting users via there ID’s and sockets to rooms when they are ready
-	Shuffling and displaying cards from the frontend and backend, and slicing them into groups. 
-	The users can only see there cards, and not there Opponents.
-	Displaying the cards on the screen to show they are in the correct piles
- Showing frontend backend capabilities

	The program is using REACT and mongoDB in order to create a website that has frontend backend capabilities.  The user will have the ability to create an account with a username and password that will use “salt” and hashing for security. The program uses sockets to connect, and disconnect users from real-time data. The chatroom will be updated on the client side, then sent to the backend via sockets and be broadcasted to the rest of the users on that page so there screen will be updated with those emojis from the chatroom. The program has the ability to link up to different users using sockets.id. The program can create rooms, only to people may be in a room at a time. Once one user joins a room, sockets updates the rest of the users on the site that someone is in the room. Once someone else joins the room and the room is full, you can click ready up. Once both users are ready, a countdown will appear from 3 to 1. This program has simulates how to create a 52 card deck and have that deck shuffled. The deck will be dealt out into 4 piles, 1 card face down, 5 cards to the side of the face down first pile,  5 cards to your hand, and 15 cards to draw pile. These piles will be demonstrated on the screen. 


### Chatroom
![](https://github.com/Junsiwoo45/Speed-Chatroom/blob/main/img/chatroom.PNG)

### Ready Up
![](https://github.com/Junsiwoo45/Speed-Chatroom/blob/main/img/readyup.PNG)

### Cards Dealt into Piles

![](https://github.com/Junsiwoo45/Speed-Chatroom/blob/main/img/dealcards.PNG)
