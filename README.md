#The Cooperative Technology Platform (CTP)

The Cooperative Technology Platform (CTP) is a JAVA framework for developing server-side, multi-threaded, distributed and concurrent applications. The framework is made up of Cooperatives instances that can be scaled by adding more instances to form Cooperative clusters.

***

##What is a Cooperative?
A Cooperative is a group of peer-level Workers (services) that cooperate to fulfill a common goal by interacting with single task queue that is both first-in-first-out (FIFO) and a key value pair or hashmap. 

##What are Workers?
Both simple and complex applications leverage services that read and write to queues. These services, called Workers in Cooperative parlance, cooperate by using ProcessObjects that share a Common Data Model (CDM) to pass information from queue to queue. Each Worker performs some computation and optionally updates or adds to the ProcessObject for further processing to accomplish their collective goal.

##Key Features

##Learn More

##License
***

CTP documentation can be found on our [wiki](ctp_main.md).

The source code can be found at our [bitbucket repository] (https://bitbucket.org/idevcoop/Automaton).

Known issues are found [here](https://bitbucket.org/idevcoop/automaton/issues?status=new&status=open).
