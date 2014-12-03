docker-activemq
===============

[Docker](https://www.docker.io/) file for the trusted build of [ActiveMQ-5.10.0](http://activemq.apache.org/).

Run the container with:

      docker pull crazycode/activemq
      docker run -p 61616:61616 -p 8161:8161 crazycode/activemq

The Broker listens on port 61616 and the Web Console on port 8161.
