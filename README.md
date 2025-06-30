
1.It's a Realtime Chatting Application that provides an interface for multiple user chatting at the same time.
2.FrontEnd Technologies- HTML, CSS
3.BackEnd Technologies- JavaScript, Node.js
4.Used Socket.io module for a two-way connection between client and server.
5.FrontEnd includes a navigation bar, Chat window and a form submit button for sending the messages.
5.First of all stored all the DOM elements in a respectives JS variable.
6.Used Audio file (tone.mp3) which gives notification on receiving the messages.
7.Everytime a new user tries to join, first of all ask his/her name and let the server know.
8.If a new user joins, receive the event from the server using eventListner.
9.Receive message from server using receive function.
10.If a user leaves the chat, tell all the other users that this user has left the chat.
11.Server Side JavaScript will handle the Socket IO connections.
12.If a new user joins, let the other users connected with server know.
13.If someone sends the message, broadcast it to other people.
14.If someone leaves the chat, let others know.
15.Right click anywhere in the file index.html and from the menu that appears select Open with Live server
16.A instance of the application will appear in the browser.
17.Copy the url from the address bar and open another instance in another tab or in incognito or on another browser.
