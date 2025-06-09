# 👤 Finding Missing Person Using AI

A face recognition-based web application built with **Streamlit**. This tool enables users to register missing or found persons and match them using AI-powered face recognition.

---

## 🚀 Features

- 📝 **Register new cases** with personal details and photo.
- 🔍 **Match faces** using advanced AI (face embeddings).
- 📂 **Browse all registered cases** with metadata.
- 🧠 **Efficient storage** of facial embeddings for quick comparisons.
- 🎛️ **User-friendly interface** created using Streamlit.

---

## 📸 Demo Screenshots

## 📸 Demo Screenshots

### 📝 Register New Case
![Register Page](../resources/image-1.png)

### 🔍 Match Found Person
![Match Result](../resources/image-2.png)

### 📂 Browse All Cases
![All Cases](../resources/image-3.png)


## 🧠 How It Works

1. **Registering a case**: User uploads an image and enters personal details.
2. The system **extracts facial embeddings** using `face_recognition` and stores them.
3. **Matching feature**: Upload a query image; the app compares its embeddings against stored ones to identify potential matches.

---

## 📦 Tech Stack

- **Python 3.8+**
- **Streamlit** – Frontend UI framework
- **face_recognition** – Facial embedding & comparison
- **OpenCV**, **NumPy**, **Pandas** – Image processing and data handling
- **Pillow (PIL)** – Image file management

---

## 🛠️ Installation & Setup

### Prerequisites

- Python 3.8 or above
- Git (optional)
- Recommended: VS Code with Python extension

### Installation Steps (Windows)

```powershell
git clone https://github.com/Rafitom/Finding-missing-person-using-AI-master.git
cd Finding-missing-person-using-AI-master

python -m venv venv
.\venv\Scripts\activate

pip install -r requirements.txt
