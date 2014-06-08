# WebAV Chat

This is a simple real-time chat application with video and audio streaming. I'm using this to learn to use the [WebRTC API](http://developer.mozilla.org/en-US/docs/Web/Guide/API/WebRTC). The architecture for the chat application will utilize the following things:

*    A [Socket.io](http://socket.io) **[signalling](http://)** server that resides on a [Node.js](http://nodejs.org) platform.
*    A [Heroku](http://heroku.com) dyno that hosts the server application.
*    A browser client application that is hosted on **[Github Pages](http://)**

To get the application up and running, you have to do the following:

*    Clone the repo
*    Install NodeJS
*    Install Grunt

## Installing NodeJS

You can get a cop of NodeJS on its site <a target="_blank" href="http://nodejs.org/">here</a> and install it. After installing it you will want to install grunt from the command line.

Now you can install Grunt's command line tools by typing out the following:

    npm install -g grunt-cli
