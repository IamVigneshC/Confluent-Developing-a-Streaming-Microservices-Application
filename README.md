# Confluent-Developing-a-Streaming-Microservices-Application

## Background

We build services using a Streaming Platform, some will be stateless: simple functions that take an input, perform a business operation and produce an output. Some will be stateful, but read-only, as in when views need to be created so we can serve remote queries. Others will need to both read and write state, either entirely inside the Kafka ecosystem, or by calling out to other services or databases. Having all approaches available makes the Kafka’s Streams API a powerful tool for building event-driven services.

https://www.confluent.io/blog/building-a-microservices-ecosystem-with-kafka-streams-and-ksql/


## Objectives

- Persist events into Kafka by producing records that represent customer orders
- Write a service that validates customer orders
- Write a service that joins streaming order information with streaming payment information and data from a customer database
- Define one set of criteria to filter records in a stream based on some criteria
- Create a session window to define five-minute windows for processing
- Create a state store for the Inventory Service
- Create one persistent query that enriches the orders stream with customer information using a stream-table join

Check out the steps

https://iamvigneshc.medium.com/confluent-developing-a-streaming-microservices-application-494680ce5e6



## Additional References:

https://docs.confluent.io/platform/current/streams/developer-guide/dsl-api.html

https://www.confluent.io/blog/distributed-real-time-joins-and-aggregations-on-user-activity-events-using-kafka-streams/

https://www.confluent.io/product/ksql/

https://github.com/confluentinc
