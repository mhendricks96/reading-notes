# Reading 14 notes

## Event driven architecture

### What’s the difference between a FIFO and a standard queue?

The functional difference is that FIFO queueu will ALWAYS keep the messages in the order they were recieved.

### How can the server be assured a message was properly received?

with a verification that is sent back to the sender.

### What classic design pattern is best represented by event driven programming?

I thiiiink its the observer pattern

### How do you test an event driven system?

I think the best way would be to have confirmations that you can then test.

## Term

### FIFO Queue

a queue that strictly preserves the first-in, first-out order.

### Pub/Sub

referencing the publisher and the subscriber.
