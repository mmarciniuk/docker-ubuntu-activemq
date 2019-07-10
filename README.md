# docker-ubuntu-activemq

To build image use command:

`docker build -t docker-ubuntu-activemq:1.0 .`

To run container use following command:

`docker run -d --rm -it -p 61616:61616 -p 8161:8161 --name docker-ubuntu-activemq docker-ubuntu-activemq:1.0`