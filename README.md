# 📝 To-Do List Application (Console-Based)

## 📌 Objective  
Create a simple console-based To-Do List manager with persistent storage.

## 🛠 Tools Used
- Python
- VS Code / Terminal
- Text file for storage (tasks.txt)

## 📦 Features
✔ Add new tasks  
✔ Remove tasks  
✔ View all tasks  
✔ Save tasks automatically  
✔ Load tasks when program starts  

## 📁 Files Included
- `todolist.py` — Main Python script  
- `tasks.txt` — Stores tasks (auto-created)

## ▶ How It Works
1. The program loads existing tasks from **tasks.txt**
2. User can select:
   - View tasks  
   - Add task  
   - Remove task  
   - Exit  
3. After each change, tasks are saved using `open()`  
4. Tasks persist even after closing the program  
