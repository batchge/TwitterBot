# TwitterBot
//Basic Twitter bot that can enter, access and interact with Twitter

# Based on the easy to follow example from bmorelli25
https://hackernoon.com/build-a-simple-twitter-bot-with-node-js-in-just-38-lines-of-code-ed92db9eb078

# node
// install node 

# enter cmd and change director
cd "..."

# initialise Node
npm init
--> this should then ask for details of the Twitter Bot, will look something like:

{
  "name": "twitter-bot",
  "version": "1.0.0",
  "description": "Nodejs Twitter Bot",
  "main": "app.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "repository": {
    "type": "git",
    "url": "git+https://github.com/bmorelli25/Twitter-Bot.git"
  },
  "author": "Brandon Morelli",
  "license": "ISC",
  "bugs": {
    "url": "https://github.com/bmorelli25/Twitter-Bot/issues"
  },
  "homepage": "https://github.com/bmorelli25/Twitter-Bot#readme",
  "dependencies": {
    "twitter": "^1.7.0"
  },
}

# run code
node app.js

# when this runs, it will run the code in app.js

