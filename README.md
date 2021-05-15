# WebRtc-Video-Call-Application

## Pakages Used In Node Js
### Socke.io,Cors middleware,express,nodemon

## Why use Cors MiddleWare?
Cors means Cross origin resourse sharing .It is important that our server validate that incoming request is valid or not.
In this middleware it take paramenters value that is <br>
***origin*** (for public api we use *) and if we want to give access a particular website or server we give address of that website .<br>
  Second parameter is ***methods*** -> In this we tell our server which request it allowed to take ( get ,post ,put ).
  
  
 # Socket Io
 Socket io uses ***websocket*** to make a 2 way full duplex communication. <br>
 websocket uses tcp/ip protol
 if we want to broadcast message to all users we uses ****emit function*** otherwise we simply open a websocket connection and listend to changes




