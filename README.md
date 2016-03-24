# Kafka-Offset-Monitor
our docker version docker version of http://quantifind.github.io/KafkaOffsetMonitor/ using alpine as the base image.

set the following envvars for the containers ("docker run -e" or whatever docker scheme you are using):
ZK=zookeeper1:2181,zookeeper2:2181...
REFRESH=10.seconds
RETAIN=2.days

the app will be exposed to port 8080, just use "docker run -p" or whatever docker scheme you use running it to expose it to the world