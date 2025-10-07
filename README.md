# Doc_Scanner_app_
---

# 📄 Document Scanner App

A simple **Streamlit-based document scanner** that detects document edges, corrects perspective, and lets you **download a scanned version** of any uploaded image.

## 🚀 Features

* Upload `.jpg` or `.png` images
* Automatic document detection
* Perspective correction using OpenCV


## 🧩 Tech

Built with **Streamlit**, **OpenCV**, **NumPy**, **Pillow**, and **streamlit-drawable-canvas**.

## ▶️ Run

```bash
pip install -r requirements.txt
streamlit run app.py
```

## 🧠 How It Works

The app detects the document boundary, applies perspective transformation, and produces a flat, scanner-like image.

---
