### **Section 11: Building RESTful CRUD APIs with Express.js – Task-Based Learning**

---

### **🔹 Task 1: Express.js Basics**

✅ **Set up an Express.js server**:
- Create a basic Express app.
- Define a simple route that responds with "Hello, World!".

✅ **Understand Middleware**:
- Implement a custom middleware function.
- Apply it to all routes using `app.use()`.

---

### **🔹 Task 2: Handling HTTP Methods**

✅ **Implement routes for different HTTP methods**:
- Create routes for GET, POST, PUT, and DELETE.
- Respond with appropriate messages for each method.

✅ **Explore Route and Request URLs**:
- Differentiate between route paths and request URLs.
- Use route parameters to handle dynamic URLs.

---

### **🔹 Task 3: Serving Static Files**

✅ **Serve static files**:
- Create a directory for static files (e.g., `public`).
- Use `express.static()` middleware to serve files from this directory.

✅ **Send JSON Responses**:
- Create an API endpoint that returns a JSON response.
- Use `res.json()` to send JSON data.

---

### **🔹 Task 4: File Storage App**

✅ **Build a basic file storage app**:
- Implement routes for uploading files.
- Store uploaded files on the server.

✅ **Handle File Uploads**:
- Use middleware like `multer` to handle file uploads.
- Implement error handling for file uploads.

---

### **🔹 Task 5: Dynamic Routing**

✅ **Implement dynamic routing**:
- Create routes with dynamic parameters.
- Access route parameters using `req.params`.

✅ **Handle Nested Directories**:
- Implement support for single-level and multi-level nested directories.
- Create routes to list files in a specified directory.

---

### **🔹 Task 6: Path Traversal Vulnerability**

✅ **Understand Path Traversal Vulnerability**:
- Identify potential vulnerabilities in file handling.
- Implement safeguards to prevent path traversal attacks.

✅ **Fix Vulnerability with Path Module**:
- Use the `path` module to sanitize file paths.
- Ensure that users can only access files within allowed directories.

---

### **🔹 Task 7: Organizing Routes**

✅ **Organize routes using Express Router**:
- Create separate route files for different resources.
- Use `express.Router()` to define routes in each file.

✅ **Implement REST API Principles**:
- Design API endpoints following REST principles.
- Use appropriate HTTP methods and status codes.

---

### **🔹 Task 8: Error Handling**

✅ **Implement Error Handling**:
- Create middleware to handle errors.
- Use `next(err)` to pass errors to the error-handling middleware.

✅ **Handle File Uploads with Multer**:
- Configure `multer` to handle file uploads.
- Show upload progress to the user.

---

### **🔹 Task 9: User Registration and Login**

✅ **Implement User Registration**:
- Create routes for user registration.
- Store user credentials securely (e.g., using bcrypt).

✅ **Implement Login Functionality**:
- Create routes for user login.
- Authenticate users and create sessions.

---

### **🔹 Task 10: Authentication and Authorization**

✅ **Provide User-Specific File Access**:
- Implement authentication middleware to protect routes.
- Ensure that users can only access their own files.

✅ **Implement Logout and User Profile**:
- Add logout functionality to clear user sessions.
- Create a user profile page to display user information.

---

### **🔹 Task 11: Advanced Express Features**

✅ **Use `res.download()` Method**:
- Implement file downloads using `res.download()`.
- Set appropriate headers for file downloads.

✅ **Use `app.route()` Method**:
- Clean up route definitions using `app.route()`.
- Chain multiple HTTP methods to a single route.

✅ **Understand `router.param()` Method**:
- Use `router.param()` to handle route parameters.
- Load user data based on the user ID in the route.

---

### **🔹 Task 12: HTTP Redirection and Form Data**

✅ **Implement HTTP Redirection**:
- Redirect users to different pages based on certain conditions.
- Use `res.redirect()` to perform HTTP redirects.

✅ **Handle Different Types of Form Data**:
- Understand the difference between `extended: true` and `extended: false` in `urlencoded` middleware.
- Handle different types of form data, including nested objects and arrays.