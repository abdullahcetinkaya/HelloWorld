example.java.helloworld
=======================

This is "Hello World" Example for Java.

The structure ``HelloWorld`` package is like this: ::

  example.java.helloworld/
  |-- HelloWorld
  |   `-- Main.java
  |-- Manifest.txt
  `-- README.md

Compile class
-------------

For compile the main class for package, execute the follow command: ::

  javac HelloWorld/Main.java

This generate the ``Main.class`` file into ``HelloWorld`` directory.

Run class
---------

For run the main class for package, execute the follow command: ::

  java -cp . HelloWorld.Main

This show the ``Hello world`` message.

Create a JAR file
-----------------

For pack the main class for package as a JAR file, execute the follow command: ::

  jar cfme HelloWorld.jar Manifest.txt HelloWorld.Main HelloWorld/Main.class


Run a JAR file
--------------

For run the JAR file packed, execute the follow command: ::

  java -jar HelloWorld.jar

This show the ``Hello world`` message.

Reference
=========

- `java - How to run a JAR file - Stack Overflow <http://stackoverflow.com/questions/1238145/how-to-run-a-jar-file>`_.

- `Setting an Application's Entry Point (The Java™ Tutorials > Deployment > Packaging Programs in JAR Files) <http://docs.oracle.com/javase/tutorial/deployment/jar/appman.html>`_.

- `https://github.com/macagua/example.java.helloworld>`_.
