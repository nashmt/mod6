# Messaging Implementation
# Status: accepted
# Context:
For Assignment 6, we were required to use ZeroMQ to handle the message passing between the business logic layer and the database. The implementation in the given working example is request-response.
# Decision:
To use ZeroMQ in a request-response messaging pattern.
# Consequences:
ZeroMQ is socket library for messaging that supports a variety of connection patterns and can be implemented across multiple platforms. It is fast and light and open-source. It also runs well with simple and fast languages like Python or even faster languages like C.  It easily suits the needs for this assignment.
