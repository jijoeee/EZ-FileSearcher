# EZ-FileSearcher 🔍

**Version:** 1.0  

EZ-FileSearcher Pro is a lightning-fast, highly visual desktop application built in Python. It solves the frustration of slow, inaccurate OS-level file searches by allowing users to deeply scan the text *inside* hundreds of documents instantly. 

Whether you are a developer grepping through code, a paralegal scanning case files, or an office worker searching for a specific spreadsheet cell, this tool finds it and highlights it for you.

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

<img width="1096" height="681" alt="image" src="https://github.com/user-attachments/assets/0388cf9c-fe30-40ba-b4df-cbd135770e19" />


<img width="1097" height="683" alt="image" src="https://github.com/user-attachments/assets/ef603498-c437-4928-9f5e-bc5129c82f26" />

