# 📝 Advanced To-Do List (CLI App)

A professional, fully-featured **Command Line To-Do Manager** built using **Python** with:

✔ Smart reminders  
✔ Timestamped PDF/CSV export  
✔ Auto-clean export folder  
✔ Categories, priorities & due dates  
✔ Subtasks support  
✔ Starred / important tasks  
✔ Sorting & searching  
✔ Persistent CSV storage  
✔ Beautiful PDF generation  
✔ Clean code architecture  

## 📁 Project Structure
```bash
📁 your-repository/
│── todo.py
│── tasks.csv              (auto created)
│── exports/               (auto created)
│     ├── tasks_export_<timestamp>.pdf
│     └── tasks_export_<timestamp>.csv
│── README.md
```

---

## ✨ Features (Everything Included)

### 🧩 Core Task Management
- Add new tasks  
- Edit task details  
- Delete with confirmation  
- Mark complete / incomplete  
- Add subtasks to any task  
- Add notes for context  
- All tasks saved automatically  

### 🗂 Data Persistence (CSV)
Tasks are ALWAYS stored in: task.csv CSV file

No manual creation needed — file auto-generates on first run.

### 🏷 Categories / Tags
Choose from:
- Work  
- Personal  
- Study  
- Others  
- Custom option

### ⭐ Importance System
Mark tasks as **Starred** — always shown at the top of the app menu.

### 📊 Sorting Options
Sort tasks by:
- Priority (highest first)  
- Due date (closest first)  
- Alphabetical order (A–Z)

### 🔍 Search System
Search tasks by:
- Title  
- Category  
- Due date  
- Notes  
- Priority  

### ⏰ Smart Reminders
On each start:
- Notifies you of tasks due **today**
- Notifies you of tasks due **tomorrow**

### 📤 Export System (with Timestamp)
Exports stored in: exports folder in PDF / CSV Formats

### 📅Time and date

Uses timestamp format: YYYY-MM-DD_HH-MM-SS


#### 🔸 PDF Export Includes:
- App title  
- Owner name  
- Export date & time  
- Task list with:
  - Title
  - Status
  - Due date
  - Priority
  - Category
  - Subtasks
  - Notes
- Footer with timestamp  
- Clean line wrapping

#### 🔸 CSV Export Includes:
All fields including subtasks stored as JSON.

### ♻ Auto Cleanup System
Automatically deletes old exports older than: 7 days
```bash
AUTO_DELETE_DAYS = 7
```
### Install Python Dependencies
```bash
pip install fpdf
```

### Running the App
```bash
python todo.py
```

### 💻 Technology Used
- Python 3.x
- CSV file handling
- JSON for subtasks
- FPDF for PDF generation
- OS & DateTime modules
- CLI-based UI

### 🚀 Why This Project is Impressive

This CLI app shows your knowledge in:

- Data persistence
- File handling
- Clean code structuring
- Export handling
- PDF generation
- User interface in CLI
- Automation concepts
- Real-world features

###  👨‍💻 Author
- Kethari Bharath Simha Reddy
- Python Developer • ML Enthusiast •  Full Stack Developer • IT Enthusiast

### ⭐ Contributing

- Contributions are welcome!
- Open PRs for features like:
   - GUI version (Tkinter / PyQt)
   - FastAPI backend
   - Voice command support
   - Cloud sync (Google Sheets / Firebase)

### 📜 License

This project is an Open Source — use it freely!

### ScreenShots
<img width="1920" height="1020" alt="Screenshot 2025-11-14 113538" src="https://github.com/user-attachments/assets/60116407-7a45-4ec7-b99d-9e6f0ac04922" />
<img width="1920" height="1020" alt="Screenshot 2025-11-14 113644" src="https://github.com/user-attachments/assets/ab6323ed-7c96-4adc-9bc9-f7cf7cc5787f" />
<img width="1920" height="1020" alt="Screenshot 2025-11-14 113728" src="https://github.com/user-attachments/assets/e18f0d97-4f57-4ce6-938f-6e04b6248e92" />

