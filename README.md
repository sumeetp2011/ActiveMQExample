# ActiveMQExample
ActiveMQ Example

Steps -
1. Setup the server
-	Download from http://activemq.apache.org/download-archives.html
- Extract and run activemq script from bin directory
- Check if http://localhost:8161 is accessible
- http://localhost:8161 is used for monitoring ActiveMQ

2. Run the consumer application. Consumer will keep checking if there is any message to consume from ActiveMQ.
3. Run producer application to send messages to the ActiveMQ. Each run of producer will send "Hello World!" message to ActiveMQ and in turn the Consumer will consume the message from ActiveMQ.

