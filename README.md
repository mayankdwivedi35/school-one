# 📱 Cloord Android WebView App

A lightweight **Android WebView application (Java)** that allows users to install and access the Cloord school management platform directly — without needing to open a browser.

---

## 🚀 Overview

This app is a **native Android wrapper** built using WebView that loads the Cloord web platform and provides a seamless app-like experience.

---

## 🎯 Purpose

Instead of repeatedly opening a browser and entering a URL, this app:

* 📲 Provides quick one-tap access
* ⚡ Improves performance and usability
* 🔐 Maintains user sessions
* 📡 Delivers real-time data from the platform

---

## ✨ Features

* 🔑 User Login & Authentication
* 📊 Student Dashboard
* 📅 Attendance Management
* 💰 Fees Tracking
* 🚌 Bus Tracking System
* 💬 Chat Integration
* 📁 Documents & Media Access
* 🔔 Notification Ready

---

## 🛠️ Tech Stack

* **Mobile App:** Android (Java, WebView)
* **Backend:** AWS (Lambda, DynamoDB, Cognito, S3)
* **Web Platform:** Next.js

---

## 📦 Installation

### 🔧 Prerequisites

* Android Studio installed
* Java SDK
* Android device or emulator

---

### ▶️ Run Project

```bash
git clone https://github.com/mayankdwivedi35/school-one.git
```

Open in **Android Studio** → Click **Run ▶️**

---

## ⚙️ Configuration

Update your base URL in the code:

```java
webView.loadUrl("https://your-domain.com");
```

---

## 📱 Build APK

From Android Studio:

```
Build → Build APK(s)
```

Or via CLI:

```bash
./gradlew assembleDebug
```

---

## 🔐 Security Notes

* Always use HTTPS
* Do not expose sensitive endpoints
* Avoid storing credentials in plain text

---

## 🤝 Contributing

1. Fork the repository
2. Create a new branch
3. Make changes
4. Submit a Pull Request

---

## 📄 License

MIT License

---

## 👨‍💻 Author

**Mayank Dwivedi**
Founder - Cloord Solution Pvt. Ltd.

---

## 🌐 About Cloord

Cloord is a complete **School & Coaching Management System** designed especially for Indian schools, including rural areas.

---

## ⭐ Support

If you find this useful:

* ⭐ Star the repo
* 🍴 Fork it
* 📢 Share it

---
