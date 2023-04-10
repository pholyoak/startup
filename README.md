# startup
<<<<<<< HEAD
=======
This is my startup File

this is my 2nd change

my 3rd change again

I learned how to commmis and push changes through vs code and git bash and then how to view them on github. I tried to merge changes and what not but mine said mine were up to date in git back when I did git pull. I really tried to figure that out but wasn't able to see what I might have done wrong. I also don't understand in my files which is my clone and which is my original. Other than that it was a helpful assignment.

Simon Javascript learn:
I learned about how to trigger functions using onclick and timeout and how to store data locally and then retreive it in different parts of the webpage
>>>>>>> cb9bc17322dcef1f4531dbe9e94540e8e94b35af

## Simon-db
I learned how to use mongodb to store data like high scores into the simon website. I also learned a lot of just terminal commands better. Like using echo to check what variable stands for what. So when I set up my mongousername, password, and host name I used echo to check if it had been done correctly. I also learned about database clusters and what code to update those data base clusters. I thought it was interesting how to use an SSH session to conenct my database cluster to my code and project that I am working on. Overall great learning experience.

## Simon-service
I learned about how to use apis to post inspirational quotes. I also learned how Node.js is used to creat out HTTp Service. I learned Curl commands better for when we used it for getscores and submitscores. I learned better how to use the web dev tools to set breakpoints to really see what the code is doing.

<<<<<<< HEAD
 
=======
## Simon-login
I learned way more about cookies. I was unaware before that cookies could be used to track users. So When a user is logged in, the cookie is added. When a user makes a secure request, the cookie is checked. When the user logs out, the cookie is removed. I also learned about endpoints and how they work with the database to store and get credentials and update the authorization cookie. I also learned how the secureApiRouter works by adding middleware function that checks if the authorization cookie is valid before passing the requres to the endpoints

## Simon-Websocket
I learned that the core feature of WebSocket is that it is fully duplexed. Meaning that after the initial connection is made from a client, using vanilla HTTP, and then upgraded by the server to a WebSocket connection, the relationship changes to a peer to peer connection where either party can efficiently send data at any time. I also found it interesting that WebSocket connections are still only between two parties. So if you want to facilitate a conversation between a group of users the server must act as the intermediary. Each peer first connects to the server, and then the server forwards messages amongst the peers.

## Simon-react
I learned the steps to convert simon to a react application 
1 Reorganize Simon
2 Commit: Commit this version in Git as the starting place for the conversion to React. It won't run, but by committing at this point can revert if necessary, instead of starting over. Make sure you keep testing and committing throughout this process.
3 Create template React application. Run npx create-react-app template-react. This creates a new directory named template-react that contains the basic configuration and template React application code.
4 Clean up template code
  Uninstall and NPM packages you won't use (e.g. stats, test)
  Delete the unnecessary create-react-app files (e.g. images)
  Rename js JSX files have jsx extension
  Replace the favicon.ico with the Simon icon
  Update manifest.json to represent Simon
  Clean up the index.html file to have the proper fields for Simon
5 Move template files to Simon
6 Convert to React Bootstrap
7 Populate App.jsx
8 Create view components
9 Create the router
10 Convert to React components
11 Set up to debug
12 Refactor play.jsx into simonGame.jsx, simonButton.jsx, and players.jsx
13 Refactor components to take advantage of React specific functionality and to create sub-components
14 Move webSocket code from play.jsx to gameNotifier.js