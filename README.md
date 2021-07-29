# Docker repository [rsantomauro/basics](https://hub.docker.com/r/rsantomauro/basics)

## This repository is for [GeneXus Deploy to Docker](https://wiki.genexus.com/commwiki/servlet/wiki?36951,How%20to%20Deploy%20an%20Application%20to%20Docker)

[Tomcat 9](https://hub.docker.com/_/tomcat) + [OpenJDK](https://openjdk.java.net/) + [Psi-Probe](https://github.com/psi-probe/psi-probe)

## KB GeneXus
Set in your property "Docker base image property" with the value "rsantomauro/basics:X"
Where "X" is the tag. 

## Docker use

In order to use this you should have in your directory a folder call ROOT with your webapp, and your tomcat-users.xml (necessary to probe):
Example of directory:

1. ROOT/
    - webappName.war
2. Dockerfile
3. tomcat-users.xml