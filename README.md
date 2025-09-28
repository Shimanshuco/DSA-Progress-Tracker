# DSA-Tracker-WebApp

A **web application** to track your DSA (Data Structures & Algorithms) practice.  
Easily log topics, problems, difficulty levels, status, dates, and notes/links to a **Google Sheet** in real-time.

---

## Features

- Add DSA problems with details:
  - Topic
  - Problem Name
  - Level (Easy / Medium / Hard)
  - Site / Link (LeetCode, Codeforces, etc.)
  - Status (Solved / Unsolved / In Progress)
  - Date Solved
  - Notes / Reference Link
- Data is automatically submitted and stored in Google Sheets.
- Responsive and modern form interface with Bootstrap.
- SweetAlert notifications on successful or failed submissions.

---

## Demo

![DSA Tracker Screenshot](https://github.com/Shimanshuco/DSA-Progress-Tracker/blob/main/DSA%20Tracker%201.png)
![DSA Tracker Screenshot](https://github.com/Shimanshuco/DSA-Progress-Tracker/blob/main/DSA%20Tracker%202.png)

Excel : 
![DSA Tracker Screenshot](https://github.com/Shimanshuco/DSA-Progress-Tracker/blob/main/Sheet.png)

---

## Tech Stack

- **Frontend:** HTML, CSS (Bootstrap 4), JavaScript
- **Backend:** Google Apps Script (Google Sheets as database)
- **Libraries:** SweetAlert2 for notifications

---

## Installation / Setup

1. **Clone this repository:**
   ```bash
   git clone https://github.com/Shimanshuco/DSA-Progress-Tracker.git
2. **Open your Google Sheet and add headers in row 2:**
   ```bash
    timestamp | Topic | Problem | Level | Site | Status | Date | Notes

3. **Deploy Google Apps Script as Web App:**
   - Go to Extensions → Apps Script
   - Paste the Apps Script code (doPost) provided.
   - Deploy → New Deployment → Web app
   - Execute as: Me
   - Who has access: Anyone
   - Copy the Web App URL.
   
5. **Update scriptURL in index.html with your Web App URL.** </br>
6. **Open index.html in a browser and start logging problems!**

---

## Contributing
  Contributions are welcome!
  - Fork the repo
  - Create a new branch (git checkout -b feature-name)
  - Commit your changes (git commit -m 'Add new feature')
  - Push to the branch (git push origin feature-name)
  - Open a Pull Request
