<h1> VMware has ended active development of this project, this repository will no longer be updated.</h1><br># Gemfire-WS
Gemfire workshop

###### Build and Install Domain 

We need to first build the Domain project and install it to local maven repository using following commands,
```
mvn clean package
mvn install
```

###### Build Gemfire-WS root project

```
mvn clean build
```

###### Run the project
Go to the specific project and execute the below command
```
mvn exec:java
```



