# sample_RESTFUL_API

 Demonstrate the role of OAuth resource server 
<h1>Guidelines</h1>
<h3>Authorization Server</h3>
This server generate JWT tokens for clients to access Resource server.</br>
Execute AuthorizationServer-0.0.1-SNAPSHOT.jar file inside the AuthorizationServer\build\libs\ Directory</br>
Issue this command in cmd to run AuthorizationServer-0.0.1-SNAPSHOT.jar file --> java -jar AuthorizationServer-0.0.1-SNAPSHOT.jar</br>
This will start the Authorization Server.</br>
</br>
<h3>Resource Server</h3>
This server reponse with a success message for the request it receives with a valid token.
Execute ResourceServer-0.0.1-SNAPSHOT.jar file inside the ResourceServer\build\libs\ Directory</br>
Issue this command in cmd to run ResourceServer-0.0.1-SNAPSHOT.jar file --> java -jar ResourceServer-0.0.1-SNAPSHOT.jar</br>
This will start the Resource Server.</br>
visit this blog post to get breif description about how this project create and how to run this servers.</br>
https://ctffreak.wordpress.com/2018/05/29/restful-api/
