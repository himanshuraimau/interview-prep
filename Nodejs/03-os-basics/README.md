### **Section 3: Basics of OS – Hands-On Tasks**

### **🔹 Task 1: Understanding CPU, Processors, and Cores**

✅ Find out **how many cores your CPU has**:

- On **Windows**: Open Task Manager → Performance → CPU
- On **Linux/macOS**: Run `lscpu` or `cat /proc/cpuinfo`
✅ Research and write down:
- Difference between **CPU vs Processor vs Core**
- What is **hyper-threading**, and how does it affect performance?

### **🔹 Task 2: Understanding OS and Kernel**

✅ Find the kernel version of your OS:

- On **Linux/macOS**: Run `uname -r`
- On **Windows (WSL)**: Run `wsl --list --verbose`
✅ Research and write:
- What is the **role of a kernel in an OS**?
- Difference between **monolithic and microkernels**.

### **🔹 Task 3: Understanding Processes & Threads**

✅ List all running processes:

- On **Linux/macOS**: Run `ps aux`
- On **Windows**: Open Task Manager (`Ctrl + Shift + Esc`)
✅ Find the **process ID (PID)** of a running process using `ps` or `tasklist`.
✅ Run a **background process** and bring it to the foreground (`&` and `fg` commands).
✅ Research and explain:
- Difference between **process vs thread**
- What is **concurrency vs parallelism**?

### **🔹 Task 4: Debugging Worker Threads in Node.js**

✅ Write a simple **Worker Thread program** in Node.js that performs a CPU-intensive task.

✅ Use `console.log(process.pid)` inside the worker to check if it's a new process.

✅ Debug it using **Node.js Debugger** or **console.log** to trace execution.

### **🔹 Task 5: Environment Variables**

✅ Set an environment variable and access it in Node.js:

- On **Linux/macOS**: Run `export MY_ENV="Hello"` and access with `process.env.MY_ENV`
- On **Windows**: Run `set MY_ENV=Hello`
✅ Create a `.env` file and load it in Node.js using **dotenv** package.

### **🔹 Task 6: Installing Windows Subsystem for Linux (WSL)**

✅ Install **WSL** and set up **Ubuntu**.

✅ Run `lsb_release -a` to verify your Linux distro inside WSL.

✅ Test Linux commands inside Windows PowerShell.

### **🔹 Task 7: Understanding Paths & Executables**

✅ Print your system **PATH variable**:

- On **Linux/macOS**: Run `echo $PATH`
- On **Windows**: Run `echo %PATH%`
✅ Find where Node.js is installed using `which node` or `where node`.
✅ Research and write:
- What happens when you type `node` in the terminal?

### **🔹 Task 8: File Permissions & Execution**

✅ Change file permissions in Linux using `chmod` (`chmod +x script.sh`).

✅ Create an **executable script** and run it (`./myscript.sh`).

### **🔹 Task 9: Understanding Process Object in Node.js**

✅ Print `process.env`, `process.pid`, `process.cwd()` in Node.js.

✅ Get the current memory usage using `process.memoryUsage()`.

✅ Create a Node.js script that logs **CPU and memory usage** every second.