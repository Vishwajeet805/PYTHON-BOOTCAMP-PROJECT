<!-- Banner -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:00b4d8,100:0077b6&height=200&section=header&text=🎓%20Student%20SQL%20Learner%20🧠&fontSize=38&fontColor=fff&fontAlignY=35&animation=twinkling" alt="banner">
</p>

<p align="center">
  <i>A Streamlit-powered AI app that lets you talk to your student database — naturally!</i>
</p>

<p align="center">
  <img src="https://img.shields.io/github/license/Vishwajeet805/PYTHON-BOOTCAMP-PROJECT?style=flat-square&color=00b4d8" />
  <img src="https://img.shields.io/github/stars/Vishwajeet805/PYTHON-BOOTCAMP-PROJECT?style=flat-square&color=90e0ef" />
  <img src="https://img.shields.io/badge/Made%20with-Streamlit-FF4B4B?logo=streamlit" />
  <img src="https://img.shields.io/badge/Powered%20by-Google%20Gemini-4285F4?logo=google" />
  <img src="https://img.shields.io/badge/Database-SQLite-blue?logo=sqlite" />
</p>

---

## 🧠 About the Project
**Student SQL Learner** transforms natural language queries into safe SQL statements to explore a student database seamlessly.  
Simply **ask in English**, and the app will interpret, execute, and explain the SQL query in **Hinglish** (English + Hindi).

---

## 🌟 Key Features
- 🔍 Convert English questions → **Safe SQL SELECT queries**
- 🧾 Maintain a searchable **query history**
- 💬 Get query explanations in charming Hinglish
- 🧠 Built-in **sample student data generator**
- 🛡️ Executes only **SELECT** queries for safety

---

## 🧰 Tech Stack

| Layer | Tools |
|:------|:------|
| Frontend | Streamlit 🎨 |
| Backend | Python 🐍 |
| Database | SQLite 💾 |
| AI Model | Google Gemini API 🤖 |
| Data Frame | Pandas 🧮 |

---

## 🧩 Database Schema

| Column | Type | Description |
|:--------|:-----|:-------------|
| NAME | VARCHAR(50) | Student name |
| CLASS | VARCHAR(50) | Grade level |
| SECTION | VARCHAR(10) | Section identifier |
| MARKS | INT | Marks obtained |

---

## ⚙️ Setup Guide

### 1️⃣ Clone this repo
```bash
git clone https://github.com/<your-username>/student-sql-learner.git
cd student-sql-learner

```

### 2️⃣ Create a virtual environment
```bash
python -m venv venv
```
For Activation
```bash
.\venv\Scripts\activate # Windows
source venv/bin/activate # macOS/Linux

```

### 3️⃣ Install dependencies
```bash
pip install -r requirements.txt

```

### 4️⃣ Add your API key
Create a `.env.local` file:'

```bash
GOOGLE_API_KEY="YOUR_API_KEY"

```

### 5️⃣ Initialize the database

```bash
python sql.py

```

### 6️⃣ Run the app
```bash
streamlit run app.py

```

---

## 🧠 Example Interaction

💬 **User:**  

```bash
“Show students who scored above 80 marks.”
```
🧮 **SQL Generated:**

```bash 
SELECT * FROM STUDENT WHERE MARKS > 80;

```

🗣️ **Response (Hinglish):**  
“Yeh students hain jin ke marks 80 se upar hain!”

---

## 🚀 Deployment Options
Deploy easily on:
- 🌐 **Streamlit Cloud**
- ⚙️ **Render**
- 🎯 **Hugging Face Spaces**

---

## 🔮 Future Roadmap
- 🧩 Support for non-SELECT queries with confirmation
- 🌍 Multi-language support
- 🤝 Integration with more LLMs

---

## 💖 Contributing
Pull requests and feature ideas are welcome! Please open an issue before submitting major changes.

```bash

git add .
git commit -m "Initial commit: Add Student SQL Learner"
git push -u origin main

```

---

## 👨‍💻 Author
Built with love by [Vishwajeet Singh](https://github.com/Vishwajeet805 🫶  
If you like this project, drop a ⭐ to support!

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0077b6,100:00b4d8&height=120&section=footer" alt="footer"/>
</p>
