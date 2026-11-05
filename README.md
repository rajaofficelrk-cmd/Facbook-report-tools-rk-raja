# 🚀 Facebook Auto Reporter

A lightweight, automated Python script built with **Selenium** to handle profile reporting tasks efficiently with a built-in live terminal dashboard, elapsed time counter, and random anti-bot delays.

---

## ✨ Features

- **Live Dashboard:** Real-time tracking of running time, total successful reports, and current progress directly in your terminal.
- **Elapsed Time Tracking:** Formatted `mm:ss` counter to track how long the automation has been running.
- **Anti-Bot Protection:** Built-in random delays (`5 to 15 seconds`) between requests to mimic human behavior and avoid automated flagging.
- **Interactive Start:** Clean command-line prompt to input target UIDs/URLs and target counts before execution.
- **Render / Cloud Ready:** Can be configured to run in headless environments using Docker and Chrome options.

---

## 🛠️ Prerequisites

Make sure you have the following installed on your system:
- **Python** (v3.8 or higher)
- **Google Chrome** browser
- **ChromeDriver** (matching your Chrome version)

---

## 📦 Installation & Setup

1. **Clone or Download** this repository to your local machine.

2. **Install Dependencies:**
   Run the following command in your terminal to install the required libraries:
   ```bash
   pip install -r requirements.txt
