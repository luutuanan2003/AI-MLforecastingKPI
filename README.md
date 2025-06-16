# 🧐 Real-Time AI Image Describer

This project is a real-time vision application that uses a webcam, Flask backend, and OpenAI's GPT-4o Vision model to describe what the camera sees — live, every second. It's designed for Raspberry Pi and desktop setups alike, and is perfect for computer vision demos, accessibility tools, or educational projects.

---

## 📸 Features

* ✅ Real-time webcam capture
* ✅ Describes camera input every second using OpenAI Vision API
* ✅ Simple browser-based frontend (HTML/JS)
* ✅ Flask backend with REST API
* ✅ Local testing with base64-encoded image requests
* ✅ Clean modular Python code (OpenCV + Pillow)

---

## 📂 Project Structure

```
project/
├── app.py                # Flask server that handles image descriptions
├── lambda_function.py     # Simulated AWS Lambda-compatible handler (optional)
├── test_client.py         # Python script to test the API with a static image
├── realtime_camera.py     # Live camera script that describes every 1s
├── index.html             # HTML UI to run from your browser
├── .env                   # API key (excluded from git)
└── test.jpg / test.png    # Sample image for testing
```

---

## 🏛️ Powered By

* [OpenAI GPT-4o](https://platform.openai.com/docs/guides/)
* Flask + flask-cors
* Pillow + OpenCV
* Vanilla HTML5 + JavaScript

---

## 📦 Use Cases

* AI-powered security camera assistant
* Accessibility tools for the visually impaired
* Educational computer vision demos
* Raspberry Pi real-time vision projects


