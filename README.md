flume-ng-kafka-source
================

This project is used for [flume-ng](https://github.com/apache/flume) to communicate with [kafka 0.7,2](http://kafka.apache.org/07/quickstart.html).

Configuration of Kafka Source
----------

    agent_log.sources.kafka0.type = com.vipshop.flume.source.kafka.KafkaSource
    agent_log.sources.kafka0.zk.connect = 127.0.0.1:2181
    agent_log.sources.kafka0.topic = all
    agent_log.sources.kafka0.groupid = es
    agent_log.sources.kafka0.channels = channel0

Notes:
---------

I've forked the project to bump the versions across the board. This affects:

- flume ng -> 1.5.0
- kafka -> now picks up the org.kafka repo in clojars
- scala 2.10

To run maven, you will need to pass -Drat.numUnapprovedLicenses=100 to mvn becasue of rat's licence checks.