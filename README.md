jms-redelivery
==============

This example demonstrates a solution for the following use case – there is a JMS message in transaction inside Mule and suddenly, before committing something bad happened. This message should be rollbacked and retried to deliver, if unable to commit for a specific number of times redirected to a dead letter queue (DLQ).
