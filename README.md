<div align="center">

# 💬 ChatApp
### Modern Realtime Chat App

![Flutter](https://img.shields.io/badge/Flutter-3.x-blue?logo=flutter)
![Dart](https://img.shields.io/badge/Dart-3.x-blue?logo=dart)
![Firebase](https://img.shields.io/badge/Firebase-Backend-orange?logo=firebase)
![Platform](https://img.shields.io/badge/Platform-Android%20%7C%20iOS-green)

A production-ready real-time chat application built using Flutter & Firebase.
Engineered with scalable architecture and clean coding principles.

</div>

---

## 📖 Project Overview

ChatApp is a real-time messaging application designed to provide a smooth and reliable user experience on Android and iOS devices.  
It integrates Flutter and Firebase to deliver a robust backend, modern UI, and high-performance real-time messaging.

---

## ✨ Key Features

- 🔐 email/password authentication  
- 💬 Real-time chat using Cloud Firestore  
- 🔔 Push notifications via Firebase Cloud Messaging  
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
- Safe handling of push notification tokens  

---

## 🚀 Future Roadmap

- Group chats  
- Voice and video messages  
- Message reactions  
- End-to-end encryption  
- CI/CD integration and automated deployment  

---

<div align="center">

## 👨‍💻 Developer

For questions or support, contact **Abdallah Zaitoun**:  
- LinkedIn: [Abdallah Zaitoun](https://www.linkedin.com/in/abdallah-zaitoun-133754348)

</div>
