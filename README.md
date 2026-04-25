# 🔍 EZ-FileSearcher (v1.1)

![Version](https://img.shields.io/badge/version-1.1-blue.svg)
![Python](https://img.shields.io/badge/python-3.10%2B-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

EZ-FileSearcher Pro is a lightning-fast, highly visual desktop application built in Python. It solves the frustration of slow, inaccurate OS-level file searches by allowing users to deeply scan the text *inside* hundreds of documents instantly. 

Whether you are a developer grepping through code, a paralegal scanning case files, or an office worker searching for a specific spreadsheet cell, this tool finds it and highlights it for you.

Update version 1.1 (26/4/2026)

1) Add Cancel button to cancel the searching progress.
2) Wrap filename text in UI for better display.
3) Fix some minor bug of the tool.

---

## ✨ Key Features

* **Multi-Format Deep Scan:** Reads standard text, code, Microsoft Office documents, and PDFs natively.
* **Non-Blocking UI:** Utilizes a threaded "Two-Phase" scanning architecture so the app never freezes, even when processing massive directories.
* **Live Progress Tracking:** Real-time percentage bar, file-scanning metrics, and session time tracking.
* **Smart Match Navigation:** Instantly snap to the exact line of your search term using the **▲** and **▼** navigation arrows. 
* **Interactive Preview:** Read file contents right inside the app. Keywords are highlighted in yellow, and the *currently active* match is highlighted in orange.
* **System Integration:** Click "Open File" to launch the document directly in your default OS application.
* **Modern GUI:** Built on `CustomTkinter` for a sleek, dark-mode native experience.

---

## 📂 Supported File Types

**Plain Text & Code:**
`.txt`, `.csv`, `.py`, `.log`, `.json`, `.md`, `.xml`, `.html`, `.ini`, `.cfg`, `.bat`, `.sh`

**Rich Documents:**
* Word (`.docx`)
* Excel (`.xlsx`)
* PowerPoint (`.pptx`)
* PDF (`.pdf`) *(Note: Extracts native text. Scanned image PDFs require OCR).*

---

## 🚀 Installation & Setup

**Prerequisites:** Ensure you have [Python 3.8+](https://www.python.org/downloads/) installed on your system.

**1. Clone the repository:**
```bash
git clone [https://github.com/jijoeee/EZ-FileSearcher.git](https://github.com/jijoeee/EZ-FileSearcher.git)
cd EZ-FileSearcher
```
2. Create a virtual environment (Recommended):
```Bash
# On Windows:
python -m venv venv
venv\Scripts\activate

# On Mac/Linux:
python3 -m venv venv
source venv/bin/activate
```
3. Install dependencies:

```Bash
pip install -r requirements.txt
```
4. Run the application:
```Bash
python ez-file-searcher.py
```
## 📸 Screenshots

<img width="2179" height="1343" alt="image" src="https://github.com/user-attachments/assets/1834a827-6586-4bb3-8fb7-e2a715840174" />

<img width="2187" height="1351" alt="image" src="https://github.com/user-attachments/assets/24fc1420-4321-4d58-8a0b-e45b2856135a" />

<img width="2175" height="1342" alt="image" src="https://github.com/user-attachments/assets/8396c0c0-b81b-4d29-8767-156f10032837" />

