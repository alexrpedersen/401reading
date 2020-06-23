# Message Queues

#### A Queue server runs independently, and is tasked with routing events and messaging between clients.

- Any connected client can “publish” a message into the server.
- Any connected client can “subscribe” to receive messages by type.

#### The Queue server has the ability to see which clients are connected, to which Queues they are attached and further, to which events they are subscribed.

## What is a message

### 
- A message is a package of information, categorized by queue and event
- 
- queue - Which general bucket does this message belong
- 
- i.e. “Database Events”, “Filesystem Events”, “Network Events”, etc
event - What event has happened

- i.e. “delete, add, update, connection lost, error”, etc.
payload - data associated with the event

- i.e. “record id, record information, error text”, etc.