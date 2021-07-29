# Docker repository [rsantomauro/basics](https://hub.docker.com/r/rsantomauro/basics)

## This repository is for GeneXus Deploy to Docker

[Tomcat 9](https://hub.docker.com/_/tomcat) + [OpenJDK](https://openjdk.java.net/) + [Psi-Probe](https://github.com/psi-probe/psi-probe)

## Docker use

In order to use this you should have in your directory a folder call ROOT with your webapp, and your tomcat-users.xml (necessary to probe):
Example of directory:

1. ROOT/
    - webappName.war
2. Dockerfile
3. tomcat-users.xml