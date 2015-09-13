# chat_app
  Components needed for chat app buildout 

##Working Go Environment
  (see Go Tutorial)

##Server
How to implement the server app?  
 Possibilities: 
  + using the `http` package included with the Go distribution
  + websocket protocol (since it is untrusted code) : this one written for Go: https://github.com/gorilla/websocket
  + (other?  suggestions welcome)
  + Redis as a message broker & db + Go + Redigo (redis client library for Go): https://github.com/garyburd/redigo
 
##Client (Front-End)
Lots of to choose from.
+  html file with Jquery/Node/other to manipulate objects in the browser?
+  just make use of Go's standard library `net/http`
+  Lots of possibilities here for UI/UX component of hackathon. 

##Time Data
Once the chat server is up and running, we need to populate a list of messages from past and future self to be sent to ourselves, either at specific times or on demand. 


