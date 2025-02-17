### **Section 12: Mastering Database Management with MongoDB and Mongoose – Task-Based Learning**

---

### **🔹 Task 1: Introduction to MongoDB**

✅ **Install MongoDB**:
- Download and install MongoDB on your local machine.
- Verify the installation by running `mongod --version` and `mongo --version`.

✅ **Explore Mongo Shell**:
- Connect to the MongoDB server using the `mongo` shell.
- Run basic commands like `show dbs`, `use <database>`, and `db.version()`.

---

### **🔹 Task 2: MongoDB Fundamentals**

✅ **Create Documents**:
- Create a database and a collection.
- Insert single and multiple documents into the collection.

✅ **Read Data**:
- Retrieve documents from the collection using `find()` with different query criteria.
- Use `pretty()` to format the output.

---

### **🔹 Task 3: Update and Delete Operations**

✅ **Update Documents**:
- Update documents using `updateOne()` and `updateMany()`.
- Use operators like `$set`, `$inc`, and `$push` to modify fields.

✅ **Delete Documents**:
- Delete documents using `deleteOne()` and `deleteMany()`.
- Understand the implications of deleting documents.

---

### **🔹 Task 4: MongoDB Datatypes**

✅ **Explore Datatypes**:
- Insert documents with different datatypes (String, Number, Boolean, Date, Array, Object).
- Use `typeof` operator in the mongo shell to check the datatype of a field.

✅ **Work with Object IDs**:
- Understand the structure and purpose of `ObjectId`.
- Query documents using `ObjectId`.

---

### **🔹 Task 5: BSON Types**

✅ **Understand BSON Types**:
- Learn about different BSON types and their use cases.
- Explore how BSON types are used to store data in MongoDB.

✅ **Practice with Datatypes**:
- Insert documents with different number types (Int32, Int64, Double).
- Understand the differences between these number types.

---

### **🔹 Task 6: Configuring MongoDB Server**

✅ **Configure MongoDB**:
- Configure the MongoDB server using a configuration file.
- Set options like `bindIp`, `port`, and `dbpath`.

✅ **Access MongoDB Remotely**:
- Configure MongoDB to allow remote connections.
- Secure your MongoDB server by setting up authentication.

---

### **🔹 Task 7: Introduction to Mongoose**

✅ **Install Mongoose**:
- Install Mongoose using `npm install mongoose`.
- Connect to a MongoDB database using Mongoose.

✅ **Define Schemas**:
- Create Mongoose schemas to define the structure of your data.
- Use different datatypes and validation options.

---

### **🔹 Task 8: Mongoose Models**

✅ **Create Models**:
- Create Mongoose models from schemas.
- Use models to perform CRUD operations on the database.

✅ **Perform CRUD Operations**:
- Create, read, update, and delete documents using Mongoose models.
- Use methods like `create()`, `find()`, `findById()`, `updateOne()`, and `deleteOne()`.

---

### **🔹 Task 9: Mongoose Relationships**

✅ **Define Relationships**:
- Define relationships between different models using `populate()`.
- Implement one-to-one, one-to-many, and many-to-many relationships.

✅ **Query Relationships**:
- Query related documents using `populate()`.
- Understand how to efficiently retrieve related data.

---

### **🔹 Task 10: Mongoose Middleware**

✅ **Implement Middleware**:
- Use Mongoose middleware to perform actions before or after certain events (e.g., saving or deleting a document).
- Implement middleware for validation, logging, and data transformation.

✅ **Handle Errors**:
- Implement error handling in Mongoose.
- Use try-catch blocks and middleware to catch and handle errors.