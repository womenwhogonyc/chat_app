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
      + 
 
 ##Client (Front-End)
Lots of to choose from.
+  html file with Jquery/Node/other to manipulate objects in the browser?
+  just make use of Go's standard library `net/http`


