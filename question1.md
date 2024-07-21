Question 1

Research:

Arrays: Arrays are a simple and efficient way to store a collection of elements. They offer fast access times but have fixed sizes, making them less flexible when data size varies.

Linked lists consist of nodes, each containing data and a reference to the next node. They’re useful for dynamic data and efficient insertions or deletions.

Stacks and Queues: These are specialized data structures for specific use cases. Stacks follow the Last-In-First-Out (LIFO) principle, while queues follow the First-In-First-Out (FIFO) principle.

Trees: Trees like Binary Trees and Balanced Trees are ideal for hierarchical data storage and efficient searching. They are commonly used in databases and file systems.

Hash Tables: Hash tables provide fast data retrieval by using a hashing function to map keys to values. They are excellent for quick lookups but may have collision issues.

Graphs: Graphs are versatile data structures for modeling complex relationships between data points, commonly used in social networks and routing algorithms.


In long polling - A client informs the server that it's ready to receive messages and will wait for them. The server only processes requests when new data is available or a timeout occurs. This can reduce the number of empty responses and provide quicker updates, which can improve the user experience.

In polling - A client sends regular requests to a server to check for updates, even if there's no new data. This can strain server resources and lead to empty responses that waste bandwidth

The WebSocket Provide full-duplex communication channels that achieve real-time data transfer and low latency. 

Task 1

For storing and retreiving message we would look at Stacks since the messaage that we first see when we open a text message is the last message sent which would be the last message stored. In /
other words it would be (LIFO)


Task 2

For receiving updates the technique most appropriate would be websocket. The Pro here is that there is an establish two way communication session between browser and server, which in this case would be two people messaging. This way messages can be sent back and forwards without having to ask every time if one side wants to receive or the other side wants to send. Polling would take a long time since it would have to wait for each input of a message. Long polling seems a bit faster since it would only start when the client, or person, is ready to receive messages. 

Task 3

" Linked lists are a powerful, flexible data structure that offers many advantages, especially in scenarios requiring dynamic memory allocation and frequent insertion and deletion operations. Their versatility makes them a fundamental component in the implementation of many more complex data structures and algorithms. " 

Linked List would be recommendaded since the memory would expands with more messages being sent back and forth. Also the app would frequently be retrieving message history to display adn deleting message or even full chats whenever the user wants. 
