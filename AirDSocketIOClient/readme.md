AirDSocketIOClient

To test with the Apk
Add this to your server Socket.IO configuration:
socket.on('messageTestApk', function(message) {
	socket.emit('message', 'Your message is '+message);
});
Thus, after connecting to the Socket and sending a message via the app, you will receive the following message by means of the OnReceived event:
Your message is ...
