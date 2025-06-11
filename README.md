# Trash-Classifier

# 🗑️ Trash Classifier – Vision-to-Text Web App

A lightweight, responsive web application that classifies images of trash into categories like plastic, glass, metal, and biodegradable using a Hugging Face model (PaliGemma) through RESTful API integration.

---
## Dataset : 
https://archive.ics.uci.edu/dataset/908/realwaste

## 🚀 Features

- 🔍 Upload and classify images of trash instantly
- 🧠 Powered by PaliGemma Vision-to-Text model (Hugging Face)
- ⚡ Built with HTML, CSS, JavaScript, and TypeScript
- 🔄 RESTful API integration for model inference
- 📱 Fully responsive and mobile-friendly interface
- ✅ Clean UI with real-time classification results

---

## 🛠️ Tech Stack

| Layer         | Technology                     |
|---------------|---------------------------------|
| Frontend      | HTML5, CSS3, JavaScript, TypeScript |
| Model API     | PaliGemma (Hugging Face)       |
| Communication | RESTful APIs                   |
| Tools         | Git, VS Code, Netlify (optional for deployment) |

---

## 🖼️ Screenshots

> Add UI screenshots here if available.

---

## 📦 Installation & Setup

```bash
# Clone the repository
git clone https://github.com/yourusername/Trash-Classifier.git
cd Trash-Classifier

# Open index.html in your browser OR serve with live-server

If you are using a backend API proxy:
```bash
npm install
npm start
```

## Usage

Upload an image of trash.

The app sends it to the backend API powered by PaliGemma.

The result is returned and displayed as a text label on the screen.

## 🔗 API Reference

Hosted on Hugging Face or custom Flask/FastAPI backend

Accepts base64 or file upload and returns JSON with classification text

```json
{
  "prediction": "Plastic bottle"
}
```



