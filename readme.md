##Node Basics Course on Team Treehouse
###Node is a server side programming environment.
The programming language is Javascript. Part of the node environment is written in C and
part is written in Javascript.

Applicatiion types that can be written are:
___
+ chat applications
+ game multiplyer applications
+ browser testing tools
+ build tools for Javascript
+ command line applications

###Node environment is:
___
+ Node is built on Chrome's Javascript runtime bound to an efficient event-loop library
+ A set of bindings to V8 for non-browser work: sockets, files, etc.
+ Node is the scripting interface to your operating system
+ Only exposes non-blocking, asynchronous interfaces
+ Ony one thread, one call stack
+ Has extended Networking possibilities for http, tcp and udp protocols.
+ Node delivers data as chunk of bytes (streams) not as whole files

###Node events:
___
A TCP server emits a 'connection' event each time some connects.
An HTTP server emits a 'data' event on each packet.

###Node application
___
A node program runs in a node process outside a browser.
It can be started on the command line with: node <scriptname>.

###Javascript
___
in browser | on server
:---|:---
embedded in Html page | embedded in system process
access to DOM | access to network resources and filesystem
js events | node events
single thread | single thread
 


