YouSync
=======

An example of how to use socket.io to sync youtube videos

Installation
=======

npm install

How to run
=======

node index.js

This will run the application on port 3000

How to use
=======
Go to http://yourip:3000 on multiple browser windows. I recommend to use the same type of browser on multiple windows/computers to make sure sound syncs.

You can then run commands from any of the instances to control the video on all instances. Following commands can be used:

- start
- restart
- pause
- stop

Stop will cause all videos to stop but may stop them from being in sync once restarted.