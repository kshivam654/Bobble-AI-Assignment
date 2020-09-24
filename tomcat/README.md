# DevOps Assignment
## Dockerfile

The folder contains two files 
    1. Dockerfile
    2. sample.war

1. Docker file 
INFORMATION:
It contains the code that creates custom docker image
 We are using tomcat server.
 apt command install the packages
 we use like apt install package_name to install any package, -y is flag to all yes durning installation
 by default the dir of linux is /user/local/
 so we copy the sample.war file there in the new folder webapps
 Then after i assign the env values as per the assignments and Exposed to 9191
 and then the run command.

NOTE: for the process your DockerDesktop must be up and running

 HOW TO RUN:

 1. clone the project from git link: 
 2. run command "npm init" (without quotes)
 3. build the docker image "docker build -t tomcat-test ." (without quotes)
 4. the above command will build the docker image.
 5. to run the docker image as container "docker run -it -d -p 9191:9191 tomcat-test" (without quotes)
 6. now hit the url "http://localhost:9191/sample/" your server must be up and running. 


Docker container link: docker pull kshivam654/test-tomcat:version3.0