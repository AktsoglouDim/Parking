to install: look at google, you need powershell (if windows and (scoop ? or some other installer if you want the easy way))<br />
<br />
to build gradle:<br />
gradle clean<br />
gradle eclipse<br />
<br />
Gradle needs to be version 4.0 >= otherwise spring does not work.<br />
<br />
Gradle currently has some useless dependencies (javax)<br />
<br />
server is created on localhost:8080<br />
<br />
It currently creates a very easy connection and receives something.<br />
<br />
The Application file (together with all the files it uses) should be in the package "hello" ( ͡° ͜ʖ ͡°) <br />
<br />
You start the server in Application.java, and start the client connecting in TestApp.java <br />