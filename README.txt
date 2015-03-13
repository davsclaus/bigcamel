Big Camel
=========

mvn clean install


Copy the .war to Apache Tomcat to deploy it

Open the web page

http://localhost:8080/bigcamel-1.0/

For example to add 5 new routes

http://localhost:8080/bigcamel-1.0/camel/hello?add=5

And to list the routes which is from the Camel API, so you can use that to compare with what Jolokia reports

http://localhost:8080/bigcamel-1.0/camel/hello?list=true

