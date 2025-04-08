# 🗓️ C# To-Do List Calendar Application

A simple console-based To-Do list manager built in C#. It organizes tasks by specific dates and allows users to:

- Add new to-do items with due dates  
- View tasks for a specific month  
- Store tasks under structured data (Year-Month-Day)  

---

## 🧠 Features

- Task objects (`To_Do_Item`) store description and due date  
- Organized by:
  - `Day_List`: Holds a list of tasks for a given day  
  - `Month_List`: Holds up to 31 `Day_List`s per month  
  - `Dictionary<int, Month_List>`: Maps `MMYYYY` keys to their monthly data  
- Console-based interface with a clean menu system  

---

## 📦 File Structure

- `Program.cs`: Main program file containing:
  - Class definitions
  - Task entry/display logic
  - In-memory journal dictionary  
- Everything is contained in a single file for ease of use  

---

## 🗂️ Example Usage
### ➕ Add a New Task
    Please enter the date in M/D/Y format:
    4/15/2025
    Please enter the description of this to do:
    Finish Software Engineering Assignment
### 📅 View Tasks for a Month
    
    Please enter Month/Year in this format (e.g., 4/2025):
    4/2025
    Output:
    4/15/2025     Finish Software Engineering Assignment

# ✍️ Author
Akin Korkmaz
Fall 2024 – C# To-Do Calendar Console Project
