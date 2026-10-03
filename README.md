# 🗣️ Text-to-Voice AI

A simple and user-friendly **Text-to-Voice application** built with **Python and Streamlit**.
The application converts user-entered text into speech, making written content easier to listen to and access.

## 🚀 Live Demo

🔗 **Try the application:**
https://text-to-voice-qfmiuf7adgbegcg2nvffyz.streamlit.app/

## 📌 Project Overview

The **Text-to-Voice AI** project allows users to enter text and convert it into spoken audio.

This project demonstrates how **Artificial Intelligence, Python, and Streamlit** can be used to build an interactive web application.

## ✨ Features

* 📝 Enter any text
* 🔊 Convert text into speech
* 🎧 Listen to the generated voice
* 🌐 Simple web-based interface
* ⚡ Easy and fast to use
* 📱 User-friendly design
* ☁️ Deployed using Streamlit Cloud

## 🛠️ Technologies Used

* **Python**
* **Streamlit**
* **Text-to-Speech (TTS)**
* **HTML/CSS** – for interface customization
* **Streamlit Cloud** – for deployment

## 📂 Project Structure

```text
Text-to-Voice/
│
├── app.py
├── requirements.txt
└── README.md
```

## ⚙️ How to Run Locally

### 1. Clone the repository

```bash
git clone https://github.com/your-username/text-to-voice.git
```

### 2. Open the project folder

```bash
cd text-to-voice
```

### 3. Create a virtual environment

```bash
python -m venv venv
```

### 4. Activate the virtual environment

**Windows:**

```bash
venv\Scripts\activate
```

### 5. Install the required packages

```bash
pip install -r requirements.txt
```

### 6. Run the Streamlit application

```bash
streamlit run app.py
```

The application will open in your browser at:

```text
http://localhost:8501
```

## 📦 Requirements

Create a `requirements.txt` file and add the libraries required by your application.

Example:

```text
streamlit
gTTS
```

> If your project uses a different Text-to-Speech library, add that library to `requirements.txt` instead.

## ☁️ Deployment on Streamlit Cloud

To deploy this project:

1. Upload the project to **GitHub**.
2. Make sure `app.py` and `requirements.txt` are in the repository.
3. Open Streamlit Community Cloud.
4. Connect your GitHub account.
5. Select your repository.
6. Select `app.py` as the main file.
7. Click **Deploy**.
8. Streamlit will install the packages from `requirements.txt`.
9. After deployment, Streamlit will provide a public URL.

## 🔄 How the Application Works

```text
User enters text
       ↓
Streamlit receives the text
       ↓
Text-to-Speech processing
       ↓
Speech/audio is generated
       ↓
User listens to the generated audio
```

## 🎯 Use Cases

This application can be useful for:

* 📚 Students
* 👨‍💻 Developers
* 👁️ Accessibility applications
* 📖 Reading assistance
* 🎧 Listeni
