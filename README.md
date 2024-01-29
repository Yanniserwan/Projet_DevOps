# Projet_DevOps
Projet CICD web

**build :**  *./gradlew* 


**to run the project locally :** *./gradlew bootRun*


**to build docker image manually :** *docker build --tag=server:latest .*


**to run manually docker container :** *docker run -d -p 8080:8080 server*

# Use the API
To use the API, you can use POSTMAN or Thunder Client, etc.

**Web app :** https://devopsprojectefrei.azurewebsites.net/api/endpoint 
In the url, don't forget to add the endpoint : students or students/id.
You can have all the information in the file ***StudentResource.java***
