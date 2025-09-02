# ⏳ ExpiryTrack - Smart Food Management System ⏳

## 🔧 Tech Stack

* **Backend**: Python, Flask
* **Computer Vision**: OpenCV
* **OCR**: Tesseract OCR
* **Database**: SQLite
* **Email Service**: SMTP

## 📄 Overview

**ExpiryTrack** is a smart food management system that helps users minimize food waste by automatically detecting and tracking expiry dates of food products using image processing. It stores product details and proactively alerts users about upcoming expiry dates along with recipe suggestions.

🔗 **Live Demo**: [https://smart-bite-5xut.onrender.com](https://smart-bite-5xut.onrender.com)

## 🔹 Features

* 📸 **Expiry Date Extraction**: Uses OpenCV and Tesseract OCR to detect expiry dates from product images.
* 📅 **Food Data Storage**: Maintains a record of products and expiry dates in an SQLite database.
* 📧 **Email Notifications**: Sends reminders before products expire.
* 🍽️ **Recipe Suggestions**: Suggests recipes based on items nearing expiry.
* 😊 **User Engagement**: Keeps users proactive in managing food items.

## 🌟 Benefits

* ✅ Cuts down food waste by up to **40%**
* 🏡 Makes kitchen and pantry management easy
* 📢 Provides timely alerts and recipe ideas

## 📁 Project Structure

```
ExpiryTrack/
├── static/
│   └── uploads/              # Folder for uploaded images
│       └── .gitkeep          # Ensures uploads folder is tracked
├── templates/                # HTML templates
│   ├── index.html
│   └── saved_items.html
├── .gitignore                # Git ignore file
├── app.py                    # Main Flask application file
├── Procfile                  # For deployment with Gunicorn
├── README.md                 # Project documentation
├── requirements.txt          # Python dependencies
```

## ⚡ Getting Started

### ✨ Prerequisites

* Python 3.x
* Tesseract OCR installed and added to system path

### 🚀 Installation

```bash
pip install -r requirements.txt
```

### ⚙️ Configuration

1. Add your SMTP credentials in `config.py`
2. Initialize the SQLite database using the provided schema
3. Run the Flask app:

```bash
python app.py
```

## 🔄 Usage

1. Upload food product images via the ExpiryTrack web interface
2. The system automatically extracts expiry dates and stores the data
3. Email alerts are sent before items expire
4. Get recipe suggestions tailored to your expiring items

## 👥 Contributing

We welcome all contributions! Fork the repo, submit pull requests, or suggest new features and improvements.

---

Built with ❤️ using Python and Flask. Manage your food smartly with **ExpiryTrack** ⏳
