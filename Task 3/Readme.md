# 📰 Task 3 – News Scraper CLI App  
_Automated Web Scraper for Top News Headlines_

This project is part of the **Elevate Labs Internship – Task 3**, where the goal is to build a **Python-based web scraper** that fetches the latest headlines from multiple public news websites.

This version includes:
- Multiple website scraping (BBC, Reuters, Al Jazeera)
- Top 10 headline filtering
- Timestamped output files
- TXT & PDF export
- A clean CLI menu
- Beautiful PDF report using FPDF

---

## 🌟 Features

### ✔ Scrape Multiple News Websites
Currently supported:
- **BBC News**
- **Reuters World News**
- **Al Jazeera News**

### ✔ Top 10 Headlines (Customizable)
You can choose:
- Top 3  
- Top 5  
- Top 10  
- Or any number

### ✔ Save Results Automatically
Outputs stored inside:
```bash
outputs/
```
<br>
### File examples:
```bash
bbc_headlines_2025-01-02_14-30-11.txt
reuters_headlines_2025-01-02_14-30-11.pdf
```

### ✔ TXT Export
Includes:
- Timestamp
- Clean list of headlines

### ✔ PDF Export (Using FPDF)
Includes:
- Title  
- Site name  
- Full timestamp  
- Headlines formatted nicely  
- Auto page breaking  

### ✔ CLI Menu
User-friendly menu:
```bash
1. Scrape single website

2. Scrape all websites

3. Exit
```

---

## 📦 Project Structure
```bash
Task 3/
├── news_scraper.py
├── outputs/
│ ├── bbc_headlines_<timestamp>.txt
│ ├── bbc_headlines_<timestamp>.pdf
│ └── ...
└── README.md
```


---

## 🛠 Installation

### Install Required Libraries
Run this command:

```bash
pip install requests beautifulsoup4 fpdf
```

### ▶️ Running the Application

Open terminal and run:

```bash
python news_scraper.py
```
### You will see a menu like:

```bash
==============================
  News Headlines Scraper CLI
==============================
1. Scrape a single website
2. Scrape all websites
3. Exit
```
Choose a site → choose number of headlines → choose output format → done!

### 📄 Example Output (TXT file)
```bash
News Headlines from BBC - Generated at 2025-01-02 14:10:22
---------------------------------------------------------

1. Global markets rally after economic report
2. New AI regulations announced by EU
3. Heavy rains hit coastal regions
4. ...

```

### 🧠 Technologies used
- Python 3+
- Requests (fetch HTML)
- BeautifulSoup4 (HTML parsing)
- FPDF (PDF generation)
- OS / DateTime modules

### 🚀 Why This Project Is Useful

This project teaches:
- Web scraping
- HTML parsing
- CLI application design
- File handling
- PDF generation
- Timestamps & file naming
- Automation scripting

### 👨‍💻 Author
Kethari Bharath Simha Reddy <br>
Python Developer • ML Enthusiast • Automation Lover<br>


### 📜 License
This project is Open Source.<br>
Feel free to modify, enhance, or reuse it.

### ScreenShots
![alt text](<Screenshot 2025-11-17 181050.png>)
![alt text](<Screenshot 2025-11-17 181246.png>)