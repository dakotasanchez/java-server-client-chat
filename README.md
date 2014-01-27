java-server-client-chat
=======================

Simple Server that connects multiple clients in a chatroom

Setup
=====

1. Have java installed
2. Have java javac and jar in your PATH

Jars are in jars directory but if needed:

Build Server
============

  cd server
  javac Server.java

Run with  
--------

  java Server
or
  java cvfe Server.jar Server *.class
  java -jar Server.jar
  
Build Client
============

  cd client
  java Client.java
  
Run with
--------

  java Client
or
  java cvfe Client.jar Client *.class resources/
  java -jar Client.jar