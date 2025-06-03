# SmartRESUMEScan

*An AI-powered resume analysis and enhancement tool built with NLP for modern tech roles..*
![Screenshot](https://github.com/Sotejaswini/SmartRESUMEscan/blob/main/screenshots/main.png?raw=true)
---

## 🔍 Overview

**SmartRESUMEScan** helps job seekers evaluate and enhance their resumes by leveraging natural language processing. It analyzes resume content, predicts potential job roles, provides keyword insights, and recommends improvements—streamlining the application process and boosting chances of success.

---

## 🎯 Features

- 📄 **Resume Parsing** — Extracts key fields like name, skills, education, and experience.
- 🧠 **Role Prediction** — Uses clustering to suggest relevant job roles.
- 🧾 **Keyword Analysis** — Highlights missing or redundant keywords.
- 🧮 **Scoring Engine** — Gives a score based on relevance, skill match, and formatting.
- 📝 **Smart Suggestions** — Offers actionable recommendations for improvement.
- 📊 **Dashboard** — Visualizes skill match, category-wise score, and resume insights.

---

## 🛠️ Tech Stack

| Area          | Tools / Libraries                     |
|---------------|----------------------------------------|
| **Frontend**  | Streamlit                              |
| **Backend**   | Python 3.9.2                         |
| **Libraries** | pandas, pyresparser, pdfminer3, NLTK, spaCy, matplotlib, Plotly |
| **NLP**       | spaCy (en_core_web_sm), NLTK, clustering |
| **Database**  | MySQL                                  |

---
## 📁 Folder Structure

```
SmartRESUMEscan/
├── App/
│ ├── Logo/
│ ├── Uploaded_Resumes/
│ ├── pycache/
│ ├── App.py
│ ├── Courses.py
│ └── requirements.txt
│
├── pyresparser/
│ ├── resume_parser.py
│
├── screenshots/
│
└── README.md

```
markdown
Copy
Edit

### 📄 Description

- **App/**: Main application logic and UI handling.
  - **Logo/**: Contains application logos or icons.
  - **Uploaded_Resumes/**: Stores user-uploaded resumes for analysis.
  - **App.py**: Entry point of the application.
  - **Courses.py**: Recommends relevant courses based on resume content.
  - **requirements.txt**: Lists dependencies to run the app.
- **pyresparser/**: Contains the resume parsing logic.
  - **resume_parser.py**: Parses and extracts details from resumes.
- **screenshots/**: Holds UI or feature demonstration images.
---
## ⚙️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/SmartRESUMEscan.git
cd SmartRESUMEscan
````

### 2. Set Up Virtual Environment

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install Requirements

```bash
cd App
pip install -r requirements.txt
python -m spacy download en_core_web_sm
```

### 4. Set Up MySQL Database

* Create a MySQL database named `cv`.
* Update `App.py` with your DB credentials.

```sql
CREATE DATABASE cv;
```

### 5. Run the App

```bash
streamlit run App.py
```

---

## Screenshots

* 📊 Skill Match and Resume Score 
![Screenshot](https://github.com/Sotejaswini/SmartRESUMEscan/blob/main/screenshots/p1.png?raw=true)
![Screenshot](https://github.com/Sotejaswini/SmartRESUMEscan/blob/main/screenshots/p2.png?raw=true)
---
