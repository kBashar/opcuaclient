We want to create a opcua client that has following capabilities.  
1. Browser: Server namespace browsing.
2. Subscriber: Node Subscription with support for callback. 
3. Reader: Node value reads, one or more nodes value
4. Writer: Writes value to one or more nodes

Based on this client library following Apps or solutions will be build  
1. Logger: Subscribes to nodes. 
   1. It will log/store data changes to DB.
   2. Data will be logged to a relational database.
   3. User will be able to map tag/node to table columns.