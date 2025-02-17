### **Section 4: Fundamentals of Node.js – Task-Based Learning**

---

### **🔹 Task 1: Understanding Node.js Modules**

✅ **Create a simple CommonJS module** (`math.js`) that exports functions for addition and subtraction. Import it in another file and use it.

✅ **Use `module.exports` vs `exports`**:

- Try exporting with `module.exports = {}` and `exports.add = function() {}` separately.
- Observe how imports behave differently in both cases.

---

### **🔹 Task 2: Exploring Module Wrapper Function**

✅ **Log `arguments` in a module** and observe how Node.js wraps your module in a function.

```
console.log(arguments);

```

✅ Explain what **`require`, `module`, `exports`, `__dirname`, and `__filename`** do in the wrapper.

---

### **🔹 Task 3: Creating a Custom Require Function**

✅ **Recreate `require()` manually**:

- Read a file (`fs.readFileSync`), wrap it in a function, and execute it using `eval()`.
- Compare the behavior with `require()`.

---

### **🔹 Task 4: Exploring ES6 Modules**

✅ **Convert a CommonJS module** to an **ES6 module** using `import` and `export`.

✅ **Try accessing `__dirname` and `__filename` in an ES6 module** and explain why it doesn't work.

✅ **Explain why both CommonJS and ES6 modules exist** and when to use each.

---

### **🔹 Task 5: Understanding NPM & Package Management**

✅ **Initialize a project with `npm init`** and explain each field in `package.json`.

✅ **Install `lodash` locally** (`npm install lodash`) and use it in a file.

✅ **Check installed packages** using `npm list` and `npm ls --depth=0`.

✅ **Install a package globally** (`npm install -g nodemon`) and run it from anywhere.

✅ **Explain `dependencies` vs `devDependencies`** in `package.json`.

---

### **🔹 Task 6: Creating & Publishing an NPM Package**

✅ **Create a simple NPM module** that exports a function and publish it to npm.

✅ **Version your package properly** and explain Semantic Versioning (`1.0.0`).

✅ **Unpublish a package** and understand npm’s restrictions on unpublishing.

---

### **🔹 Task 7: Understanding npx**

✅ **Run a package without installing it** using `npx cowsay "Hello Node.js"`.

✅ **Create a CLI tool** using `#!/usr/bin/env node` (Shebang) and run it with `npx`.

---

### **🔹 Task 8: File System (FS) Module – Hands-on**

✅ **Read a file using `fs.readFileSync()`** and print its content.

✅ **Write to a file using `fs.writeFileSync()`**.

✅ **Rename, delete, and copy a file** using Node.js file system operations.

---

### **🔹 Task 9: Build a Word Counter CLI Tool**

✅ **Create a command-line tool** that:

- Takes a file as input (`node word-counter.js input.txt`).
- Reads the file content using `fs.readFileSync()`.
- Counts the number of words and prints the result.
✅ **Make it executable** by adding a shebang (`#!/usr/bin/env node`).
✅ **Publish it on npm** and try running it using `npx`.