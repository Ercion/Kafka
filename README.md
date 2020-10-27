# Kafka
This repository contains useful Kafka examples


# Create Topic
bin/kafka-topics.sh --create --bootstrap-server localhost:9092 \
--replication-factor 1 \
--partitions 1 \
--topic your_topic_name

# List Topics
bin/kafka-topics.sh --list --bootstrap-server localhost:9092
