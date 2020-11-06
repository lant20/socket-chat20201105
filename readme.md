Basic socket chat to test functionality on Heroku.
Code taken from https://github.com/plhwin/nodejs-socketio-chat.
-Cleaned references to alipay in the css file.
-Retrieving socket.io library from a cdn in the html file.
-Removed the protocol of the socket connection url (mixed content error in FF).

To adapt to any heroku dyno, edit the socket connection url on line 99 in the static/client.js file.
