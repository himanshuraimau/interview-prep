### **Section 10: Networking with Core Node.js Modules – Task-Based Learning**

---

### **🔹 Task 1: UDP Server and Client**

✅ **Create a UDP Server**:
- Use the `dgram` module to create a UDP server.
- Implement message handling.

✅ **Create a UDP Client**:
- Send messages to the UDP server.
- Receive responses from the server.

---

### **🔹 Task 2: Transferring Files Using UDP**

✅ **Implement File Sender**:
- Read a file in chunks.
- Send each chunk as a UDP message.

✅ **Implement File Receiver**:
- Receive UDP messages.
- Reassemble the file from the chunks.

---

### **🔹 Task 3: TCP Server and Client**

✅ **Create a TCP Server**:
- Use the `net` module to create a TCP server.
- Handle multiple clients.

✅ **Create a TCP Client**:
- Connect to the TCP server.
- Send and receive messages.

---

### **🔹 Task 4: Transferring Files Using TCP**

✅ **Implement TCP File Sender**:
- Read a file in chunks.
- Send each chunk over a TCP connection.

✅ **Implement TCP File Receiver**:
- Receive TCP messages.
- Reassemble the file.

---

### **🔹 Task 5: HTTP Server Using `net` Module**

✅ **Create an HTTP Server**:
- Use the `net` module to handle TCP connections.
- Parse HTTP requests manually.
- Send HTTP responses.

✅ **Inspect HTTP Headers**:
- Analyze HTTP request and response headers.
- Implement handling for common headers.

---

### **🔹 Task 6: HTTP Server Using `http` Module**

✅ **Create an HTTP Server**:
- Use the `http` module to create an HTTP server.
- Handle different HTTP request methods (GET, POST, etc.).

✅ **Implement Response Status Codes**:
- Send appropriate HTTP status codes for different scenarios.
- Handle errors and redirects.

---

### **🔹 Task 7: HTTP Client**

✅ **Create an HTTP Client**:
- Use the `http` or `https` module to make HTTP requests.
- Handle HTTP responses.

✅ **Analyze HTTP Request/Response**:
- Understand the structure of HTTP requests and responses.
- Implement request and response parsing.

---

### **🔹 Task 8: Web Server**

✅ **Create a Basic Web Server**:
- Serve static files (HTML, CSS, JavaScript).
- Implement routing for different URLs.

✅ **Implement File Upload**:
- Handle file uploads using the `http` module.
- Store uploaded files on the server.

---

### **🔹 Task 9: Online Storage Platform**

✅ **Implement File Preview**:
- Serve files for preview in the browser.
- Handle different file types.

✅ **Implement File Download**:
- Allow users to download files from the server.
- Implement access control.

---

### **🔹 Task 10: Advanced Features**

✅ **Implement File Rename**:
- Allow users to rename files.
- Update file metadata.

✅ **Implement File Delete**:
- Allow users to delete files.
- Handle file deletion and cleanup.

✅ **Add Progress Tracking**:
- Show upload progress to the user.
- Implement client-side progress updates.