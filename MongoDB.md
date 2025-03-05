**MongoDB Course**

**Introduction to MongoDB**
MongoDB is a NoSQL database that provides high performance, high availability, and easy scalability. Unlike traditional relational databases, it stores data in JSON-like documents with dynamic schemas.

### **Module 1: Basics of MongoDB**
1. **What is MongoDB?**
   - MongoDB is a document-based NoSQL database designed for scalability and flexibility.
   - Stores data in BSON (Binary JSON) format.
   - Supports CRUD (Create, Read, Update, Delete) operations.

2. **Installing MongoDB**
   - Download and install MongoDB from [official website](https://www.mongodb.com/try/download/community).
   - Start MongoDB Server:
     ```bash
     mongod
     ```
   - Open MongoDB shell:
     ```bash
     mongo
     ```

### **Module 2: MongoDB Shell Basics**
1. **Basic Commands**
   ```javascript
   show dbs  // List all databases
   use myDB  // Switch to database myDB
   db.createCollection("users")  // Create collection
   show collections  // List collections
   ```

2. **Inserting Data**
   ```javascript
   db.users.insertOne({name: "Alice", age: 25, city: "New York"})
   db.users.insertMany([
       {name: "Bob", age: 30},
       {name: "Charlie", age: 28}
   ])
   ```

### **Module 3: Querying Data**
1. **Finding Documents**
   ```javascript
   db.users.find()  // Retrieve all documents
   db.users.find({name: "Alice"})  // Find specific user
   db.users.find({age: {$gt: 25}})  // Users with age > 25
   ```

2. **Updating Documents**
   ```javascript
   db.users.updateOne({name: "Alice"}, {$set: {age: 26}})
   db.users.updateMany({}, {$set: {country: "USA"}})
   ```

3. **Deleting Documents**
   ```javascript
   db.users.deleteOne({name: "Alice"})
   db.users.deleteMany({age: {$gt: 30}})
   ```

### **Module 4: Indexing and Aggregation**
1. **Indexing**
   ```javascript
   db.users.createIndex({name: 1})
   ```

2. **Aggregation Framework**
   ```javascript
   db.users.aggregate([
       {$match: {age: {$gt: 25}}},
       {$group: {_id: "$city", total: {$sum: 1}}}
   ])
   ```

### **Module 5: Working with Relationships**
1. **Embedding Documents**
   ```javascript
   db.orders.insertOne({
       customer: "Alice",
       items: [{product: "Laptop", price: 1200}, {product: "Mouse", price: 30}]
   })
   ```

2. **Referencing Documents**
   ```javascript
   db.customers.insertOne({_id: 1, name: "Alice"})
   db.orders.insertOne({customerId: 1, product: "Laptop"})
   ```

### **Module 6: Using MongoDB with Python**
1. **Connecting to MongoDB with Python**
   ```python
   from pymongo import MongoClient
   client = MongoClient("mongodb://localhost:27017/")
   db = client["mydatabase"]
   collection = db["users"]
   ```

2. **Inserting Data**
   ```python
   user = {"name": "Alice", "age": 25}
   collection.insert_one(user)
   ```

3. **Querying Data**
   ```python
   for user in collection.find():
       print(user)
   ```

### **Module 7: Advanced MongoDB Features**
1. **Replication**
   - MongoDB supports replica sets for high availability.

2. **Sharding**
   - Horizontal scaling by distributing data across multiple servers.

3. **MongoDB Atlas**
   - Cloud-based MongoDB service for managed database hosting.

This MongoDB course covers all essential concepts, from basic to advanced, with practical examples. Let me know if you need any modifications or additional topics!

