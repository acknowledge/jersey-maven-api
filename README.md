# Basic template for a JAVA API

In this template, there are two versions. The first one use Jersey and the second use standard Servlet. Maven is used to manage dependences.

## Configuration

This template works with a Tomcat8 server.

## Jersey method

The Jersey version is defined in the "rest" package with the class HelloWorldService. The paths are defined in the file but the root path is defined in the web.xml file.

URL to access it : http://localhost:8080/JerseyTest/rest/hello/heeey

## Servlet method

The Servlets are on the "servlet" package. Here is the Test method to demonstrate the way it works. The routes are defined directly in the file here.

URL to access it : http://localhost:8080/JerseyTest/Test
