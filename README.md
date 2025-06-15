# 🎯 Face Recognition Attendance System

A real-time face recognition-based attendance system using **Streamlit**, **OpenCV**, and the **face_recognition** library. The application enables automatic attendance marking using a live webcam feed. It also provides a secure admin interface to upload new known faces and export attendance data.

---

## 📌 Features

- 🔐 **Admin Login** for secure access
- 📸 **Live webcam face recognition**
- ✅ **Automatic attendance marking** with date and time
- ⬆️ **Upload new known faces** through the UI
- 🧠 Uses `face_recognition` for high-accuracy facial matching
- 📁 **Exports attendance** data to `attendance.csv`
- 🖼️ Real-time camera preview in Streamlit

---

## 🧰 Tech Stack

- **Python 3.10**
- **Streamlit**
- **OpenCV**
- **face_recognition**
- **Dlib**
- **Pillow (PIL)**

---

## 🛠️ Installation


# Clone the repository
```bash
git clone https://github.com/your-username/face-recognition-attendance.git
cd face-recognition-attendance
```
# Create a virtual environment (recommended)
```
python -m venv faceenv
```
# Activate the environment
# Windows
```
faceenv\Scripts\activate
```
# macOS/Linux
```
source faceenv/bin/activate
```

# Install dependencies
```
pip install -r requirements.txt
```
# Usage
```
streamlit run app.py
```
Once the app launches:

1. Log in as admin to begin recognition

2. Allow access to the webcam when prompted

3. Recognized users will be automatically marked in attendance.csv
