<div align="center">

# 💬 ChatApp
### Modern Realtime Chat App

![Flutter](https://img.shields.io/badge/Flutter-3.x-blue?logo=flutter)
![Dart](https://img.shields.io/badge/Dart-3.x-blue?logo=dart)
![Firebase](https://img.shields.io/badge/Firebase-Backend-orange?logo=firebase)
![Platform](https://img.shields.io/badge/Platform-Android%20%7C%20iOS-green)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

A fast, secure, and professional chat application designed to showcase modern software engineering skills.

</div>

---

## 📖 Project Overview

ChatApp is a real-time messaging application designed to provide a smooth and reliable user experience on Android and iOS devices.  
It integrates Flutter and Firebase to deliver a robust backend, modern UI, and high-performance real-time messaging.

---

## ✨ Key Features

- 🔐 Secure email/password authentication  
- 💬 Real-time chat using Cloud Firestore  
- 🟢 Online/offline user status  
- 📷 Image sharing via Firebase Storage  
- 🔔 Push notifications via Firebase Cloud Messaging  
- 🌙 Dark mode support  
- 📌 Last seen & message timestamps  
- 🔍 User search functionality  
- 🗑️ Message deletion  

---

## 🏗️ Architecture

```
lib/
 ┣ core/
 ┃ ┣ constants/
 ┃ ┣ theme/
 ┃ ┗ utils/
 ┣ models/
 ┣ services/
 ┣ providers/
 ┣ screens/
 ┣ widgets/
 ┗ main.dart
```

**Architecture Principles:**  
- Separation of Concerns  
- Independent service layer for Firebase interactions  
- Organized state management (Provider / Riverpod)  
- Reusable UI components  
- Professional folder organization  

---

## 🛠️ Tech Stack

| Layer | Technology |
|--------|----------|
| UI Framework | Flutter |
| Programming Language | Dart |
| Authentication | Firebase Auth |
| Database | Cloud Firestore |
| Storage | Firebase Storage |
| Notifications | Firebase Cloud Messaging |

---

## ⚙️ Setup & Run

### 1️⃣ Clone the project

```bash
git clone https://github.com/username/chatapp.git
cd chatapp
```

### 2️⃣ Install dependencies

```bash
flutter pub get
```

### 3️⃣ Firebase Setup

1. Create a new Firebase project  
2. Enable Authentication, Firestore, Storage, Cloud Messaging  
3. Download `google-services.json` and place it in `android/app/`  

### 4️⃣ Run the app

```bash
flutter run
```

---

## 🔐 Security

- Firestore security rules applied  
- User authentication required to access chat  
- Secure storage for images and files  
- Safe handling of push notification tokens  

---

## 🚀 Future Roadmap

- Group chats  
- Voice and video messages  
- Message reactions  
- End-to-end encryption  
- CI/CD integration and automated deployment  

---

## 🤝 Contribution

1. Fork the repository  
2. Create a new branch  
3. Make clear commits  
4. Submit a Pull Request  

---

## 📜 License

MIT License

---

<div align="center">

## 👨‍💻 Developer

Abdallah Zaitoun  
Flutter Developer | Mobile Engineer

</div>
