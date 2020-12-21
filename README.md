Build the application with mvn:spring-boot:run.

The application wi start on port 8090. 

The below url will be used to populate Services and URL's

http://localhost:8090/urlService/Service

It takes input in the below format : 

{   
    "url":"http://localhost:8091",
    "userId":"User123",
    "service":"Service1"
}

It supports GET, POST and DELETE requests.

The sample application to be monitored is available in the git repo https://github.com/shamik123/PolledApplication.git. The sample monitored application will be run on port 8091.

The Application provides a simple UI to show a listing of the Service and their status.
