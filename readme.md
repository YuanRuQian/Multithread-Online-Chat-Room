# HTTP/WebSocket Local Server + Web Client + Android Client

## How to start the local service and access clients
- run server/src/Main
- go to [localhost:8080/index.html](http://localhost:8080/index.html) for the web client
- run android-client/AndroidChatClient for the Android client

## Demo Screenshot
![web client](images/web-client.png)

![android client log in page](images/LogInPage.png)

![android client chat page](images/ChatRoomPage.png)

![server console log](images/server-console-log.png)

## Extra features
- Show active / online users in a chat room
- Show time / date info of a message
- Keep track of history messages sent to each room, when a new client joins, send all history messages to the client
- Retain history messages in local files
- Support multiple new lines
- Support all UTF-8 languages / emoji
- Prevent duplicate user from joining the same room
- Strip HTML tags in messages