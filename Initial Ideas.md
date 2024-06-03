# Task Queue



**Job Queue:**

- SimpleQueue at first maybe later we can think about using a PriorityQueue
- Need to think about partitioning / sharding
- Deduplication ID
- Message ack, retry, DLQ??
- Do I use RabbitMQ or Kafka or some other existing product or try building something myself




**Worker Management:**

- Maintaining a pool of workers
- Master pushes jobs to free workers
- periodic health and status update to Master which  runs on a separate thread ????
- gRPC better than http ?? maybe use ws for to-fro comms ??






