## 📦 Full Project Download (With Model & Dataset)

Due to GitHub file size limitations, some large files such as the trained model (.h5) and dataset are not included in this repository.

You can download the **complete project (fully working with model and dataset)** from Google Drive:

👉 https://drive.google.com/file/d/1ppdQ8abDSvuR4ugWJtB6Zb0ZNb5-X1zL/view?usp=sharing

After downloading:
1. Extract the ZIP file  
2. Open the project folder  
3. Run the application using:
   ```bash
   python app.py# stress-detection-system
AI-powered web application for real-time and chronic stress detection using deep learning, computer vision, and user feedback-based continuous learning.

# 🧠 Real-Time Stress Detection System using Deep Learning

## 📌 Overview
This project is a **Real-Time Stress Detection System** that uses **Deep Learning and Computer Vision** to analyze facial expressions and predict stress levels.

The system supports:
- ⚡ **Acute Stress Detection** (real-time using webcam or image)
- 🧠 **Chronic Stress Monitoring** (long-term analysis using surveys, video, and reports)

A unique feature of this system is its **feedback-based learning mechanism**, where users can validate or correct predictions, allowing continuous improvement of the model over time.

---

## 🎯 Key Features

- 🎥 Real-Time Webcam Detection  
- 🖼️ Image Upload Support  
- 🧠 CNN-based Emotion & Stress Prediction  
- 🔄 Feedback-Based Continuous Learning  
- 👤 User Authentication (Login/Register)  
- 🗄️ MongoDB Database Integration  
- 📄 PDF Report Generation  
- 📊 Emotion Confidence Charts  
- 📋 Daily Stress Survey (Chronic Mode)  
- 🎥 Video-Based Stress Analysis  

---

## 🛠️ Tech Stack

- **Python**
- **Flask**
- **TensorFlow / Keras**
- **OpenCV**
- **MongoDB**
- **HTML, CSS, JavaScript**
- **ReportLab**

---

## 🧠 How It Works

1. User logs in or registers  
2. Selects detection mode (Acute / Chronic)  
3. Captures image via webcam or uploads image  
4. Face is detected using OpenCV  
5. Image is preprocessed (grayscale + resized)  
6. CNN model predicts emotion  
7. Stress score is calculated  
8. Result displayed with confidence charts  
9. User provides feedback (correct/incorrect)  
10. Data stored for future model improvement  

---

## 📦 Full Project Download (With Model & Dataset)

Due to GitHub file size limitations, some large files such as the trained model (.h5) and dataset are not included in this repository.

You can download the **complete project (fully working with model and dataset)** from Google Drive:

👉 https://drive.google.com/file/d/1ppdQ8abDSvuR4ugWJtB6Zb0ZNb5-X1zL/view?usp=sharing

After downloading:
1. Extract the ZIP file  
2. Open the project folder  
3. Run the application using:
```bash
python app.py
📦 Model Download

The trained deep learning model is hosted separately:

👉 https://drive.google.com/file/d/1ppdQ8abDSvuR4ugWJtB6Zb0ZNb5-X1zL/view

📸 Screenshots
🏠 Home Page

🔐 Login Page

📝 Register Page

🎯 Dashboard (Acute Detection)

📊 Prediction Result

🔄 Feedback System

🧠 Chronic Stress Detection

📋 Daily Survey

📄 Weekly Report

📂 Project Structure
stress-detection-system/
│
├── app.py
├── auth.py
├── main.py
├── forms.py
├── models.py
├── extensions.py
│
├── templates/
├── static/
├── images/
│
├── test_webcam.py
├── requirements.txt
├── README.md
⚙️ Installation & Setup
git clone https://github.com/your-username/stress-detection-system.git
cd stress-detection-system

python -m venv venv
venv\Scripts\activate   # Windows

pip install -r requirements.txt
python app.py

Open in browser:

http://127.0.0.1:5000/
🌐 Deployment

You can deploy using:

Render
Railway

Start command:

gunicorn app:app
🔄 Feedback-Based Learning

The system improves over time using user feedback:

✅ Correct prediction → stored as training data
❌ Incorrect → user provides correct label
📈 Data used for future model retraining
🚧 Challenges Faced
Real-time webcam processing
Integrating ML model with Flask
Handling image preprocessing
Managing large model files
Building a full-stack ML application
🔮 Future Improvements
Automatic model retraining
Improve accuracy with larger dataset
Enhance UI/UX
Mobile compatibility
Cloud scalability
📌 Note
GitHub repository contains only the clean source code
Google Drive contains the full project with model and dataset
This approach follows standard practices for handling large ML files
👨‍💻 Author

Adil Qateeb
Aspiring Python Developer | AI & Data Science Student

⭐ Conclusion

This project demonstrates the ability to build a complete AI-powered system, combining deep learning, computer vision, and full-stack development with a feedback-driven learning mechanism.
