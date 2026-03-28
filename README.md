# StreamStore 

StreamStore is a Simple **Apache Kafka** project built to practice a  **producer → topic → consumer** workflow using **Python**.

## Brief
- `producer.py` publishes an **order** message (JSON) to the Kafka topic: `orders`
- `tracker.py` subscribes to `orders` and prints received messages
- Kafka runs locally using **Docker Compose** (KRaft mode, no ZooKeeper)

## Tools & Technologies
- **Python**
- **Apache Kafka**
- **confluent-kafka (Python client)**: `Producer` / `Consumer`
- **Docker + Docker Compose**
- Kafka image: `confluentinc/cp-kafka:7.8.3`
