# 📚 BookScope

**BookScope** is a simple yet powerful book search web app that allows users to explore books using the Open Library API. It helps users quickly find details like title, author, and year of publication — all in a clean, responsive interface.

> 🔄 This project is adapted from [PrajwalaY26/BookFinder](https://github.com/PrajwalaY26/BookFinder) and customized for my own learning and usage.

---

## 🚀 Features

- 🔍 **Search by title, author, or keyword**
- 📖 **Displays book details** including title, author, and publication year
- 🖼️ **Book cover preview**
- ⚡ **Fast and lightweight Flask backend**
- 🎨 **Minimal and clean UI design**

---

## 🛠️ Tech Stack

| Component     | Tech Used             |
|---------------|------------------------|
| Frontend      | HTML, CSS, JavaScript  |
| Backend       | Python (Flask)         |
| API           | Open Library API       |
| Runtime       | Localhost / Python App |

---

## 📦 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/Pavithrars2004/BookScope.git
cd BookScope
```

### 2. Create a Virtual Environment (Optional but Recommended)

```bash
python -m venv venv
# Activate on Windows:
venv\Scripts\activate
# Or on macOS/Linux:
source venv/bin/activate
```

### 3. Install Required Libraries

```bash
pip install flask requests
```

### 4. Run the App

```bash
python app.py
```

Visit: `http://127.0.0.1:5000` in your browser

---

## 🗂️ Project Structure

```
BookScope/
├── static/
│   └── style.css
├── templates/
│   ├── index.html
│   └── result.html
├── app.py
├── README.md
└── requirements.txt
```

---

## 🔍 Sample Search Keywords

- `Pride and Prejudice`
- `J.K. Rowling`
- `Self Help`
- `Science Fiction`

---

## 🔧 Future Improvements

- Add dark/light mode toggle
- Show more book metadata (subjects, ISBN, etc.)
- Allow book saving to favorites (local/session)
- Deploy using Render/Heroku

---
