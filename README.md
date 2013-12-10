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

Speical Thanks
---------

In fact I'm a newbie in Java. I have learnt a lot from [flumg-ng-rabbitmq](https://github.com/jcustenborder/flume-ng-rabbitmq). Thanks to [Jeremy Custenborder](https://github.com/jcustenborder).

