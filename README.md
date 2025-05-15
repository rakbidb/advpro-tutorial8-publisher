a. How much data your publisher program will send to the message broker in one run?

In main() function on main.rs, the program is sending 5 messages in one run.

b. The url of: "amqp://guest:guest@localhost:5672" is the same as in the subscriber program, what does it mean?

It means both subscriber and publisher are connecting to the same AMPQ broker. The publisher publishes to the same broker as the one that the subscribers are subscribed to.