# chat_app
  Headers include the main components needed for chat app buildout. There are many different ways to go about making your chat app. 

##Working Go Environment
See Go Tutorial
 
##Server
How to implement the server app?  
 Possibilities: 
  + using the `http` package included with the Go distribution

###Websocket 
  + https://godoc.org/golang.org/x/net/websocket
  + this one written for Go: https://github.com/gorilla/websocket
  + minimalist websocket for Go: github.com/olahol/melody

##Client (Front-End)
Lots of to choose from.
+  html file with Jquery/Node/other to manipulate objects in the browser?
+  rely solely on Go's extensive standard libraries `net/http` and others
+  nonstandard libraries: HTTP web framework written in Go https://github.com/gin-gonic/gin
+  Lots of creative license here for front end component of hackathon. 

##OTHER

+ If you already have a Go environment up-and-running, why not consider a `dockerfile` for your setup to keep your system clean? 
+ Time Data
Once the chat server is up and running, we need to populate a list of messages from past and future self to be sent to ourselves, either at specific times or on demand. 
+ Redis as a message broker & db + Go + Redigo (redis client library for Go): https://github.com/garyburd/redigo


