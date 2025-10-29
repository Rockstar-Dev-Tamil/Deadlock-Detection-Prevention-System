# 🧠 Deadlock Detection & Prevention System

### 👨‍💻 Developed by:
**Jayabalaji**, **Simon**, **Selvabalan**


## 📘 Overview
The **Deadlock Detection & Prevention System** is an interactive **web-based simulator** built using **HTML, CSS, and JavaScript**.  
It visually demonstrates how **deadlocks** occur in operating systems and how they can be **detected and prevented** using various algorithms and strategies.

The tool provides a **real-time graphical representation** of processes and resources through a **Resource Allocation Graph (RAG)**.  
Users can create processes, allocate resources, make requests, and visually observe **deadlock formation** and **prevention** in action.


## 🎯 Objectives
- To simulate **process-resource interactions** in an operating system.
- To visualize **deadlock conditions** using a Resource Allocation Graph.
- To implement and demonstrate **deadlock detection** via cycle detection.
- To apply **deadlock prevention techniques**, such as resource ordering and safe state validation.
- To provide an **interactive learning tool** for OS students and enthusiasts.


## 🏗️ System Architecture

The architecture of the system consists of the following key modules:

1. **User Interface (UI):**
   - Accepts user input for process and resource creation.
   - Allows adding and removing connections (requests and allocations).

2. **Main Control Module:**
   - Handles logic between user input, graph data, and visual updates.

3. **Resource Allocation Graph (RAG):**
   - Dynamically represents processes and resources as nodes and edges.

4. **Deadlock Detection Module:**
   - Detects circular dependencies using a **Cycle Detection Algorithm**.

5. **Deadlock Prevention Module:**
   - Implements **Resource Ordering** and **Safe State Validation** to prevent circular waits.

6. **Visualization and Logging:**
   - Displays real-time updates, highlights deadlocked nodes, and maintains an event log.



## ⚙️ Algorithms Used

### 🔹 Deadlock Detection (Cycle Detection)
- Builds a directed graph with processes and resources.
- Uses **Depth-First Search (DFS)** to identify cycles.
- Highlights nodes involved in deadlock visually.

### 🔹 Deadlock Prevention
- Implements **resource ordering** and **safe state checks**.
- Prevents resource requests that lead to unsafe system states.

### 🔹 (Optional) Deadlock Avoidance
- Can be extended to include **Banker’s Algorithm** for safe resource allocation.



## 🧩 Features
- Interactive **graph-based visualization** of processes and resources.
- Real-time **deadlock detection** with visual highlights.
- **Event logging** for each operation.
- **Prevention toggle** for safe resource ordering.
- Clean and simple **web interface** (no extra installations needed).


## 🖼️ Sample Output
- Blue rectangles represent **Processes (P)**.  
- Green circles represent **Resources (R)**.  
- Arrows indicate **requests (P → R)** or **allocations (R → P)**.  
- Red highlights indicate **deadlocked nodes**.  

Example:  
<img width="960" height="510" alt="image" src="https://github.com/user-attachments/assets/15ac5af5-bb19-4198-992a-927c5358b68f" />
