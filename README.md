<div align="center">

# 💬 ChatApp
### Scalable Realtime Messaging Application

![Flutter](https://img.shields.io/badge/Flutter-3.x-blue?logo=flutter)
![Dart](https://img.shields.io/badge/Dart-3.x-blue?logo=dart)
![Firebase](https://img.shields.io/badge/Firebase-Backend-orange?logo=firebase)
![Platform](https://img.shields.io/badge/Platform-Android%20%7C%20iOS-green)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

A production-ready real-time chat application built using Flutter & Firebase.
Engineered with scalable architecture and clean coding principles.

</div>

---

## 📖 Overview

ChatApp is a modern messaging application designed to deliver a smooth and secure real-time communication experience.

The project demonstrates:

- Clean Architecture principles
- Modular project structure
- Firebase backend integration
- Reusable UI components
- Scalable state management

---

## ✨ Core Features

- 🔐 Secure Email & Password Authentication
- 💬 Real-time Messaging using Firestore Streams
- 🟢 Online / Offline User Presence
- 📷 Image Sharing (Firebase Storage)
- 🔔 Push Notifications (Firebase Cloud Messaging)
- 🌙 Dark Mode Support
- 📌 Last Seen & Timestamps
- 🔍 User Search
- 🗑️ Message Deletion

---

## 🏗️ Architecture

The project follows a scalable layered structure:

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

### Architectural Concepts

- Separation of Concerns
- Service Abstraction Layer
- Reusable Widgets
- Provider / Riverpod State Management
- Clean Folder Organization

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|------------|
| UI Framework | Flutter |
| Language | Dart |
| Authentication | Firebase Auth |
| Database | Cloud Firestore |
| Storage | Firebase Storage |
| Notifications | Firebase Cloud Messaging |

---

## 📱 Screenshots

Create a folder named:

```
screenshots/
```

Add images, then include:

```markdown
<p align="center">
  <img src="screenshots/1.png" width="250">
  <img src="screenshots/2.png" width="250">
  <img src="screenshots/3.png" width="250">
</p>
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/yourusername/chatapp.git
cd chatapp
```

### 2️⃣ Install dependencies

```bash
flutter pub get
```

### 3️⃣ Firebase Setup

1. Create a new Firebase Project
2. Enable:
   - Authentication (Email/Password)
   - Cloud Firestore
   - Firebase Storage
   - Cloud Messaging
3. Download `google-services.json`
4. Place it inside:

```
android/app/
```

### 4️⃣ Run the application

```bash
flutter run
```

---

## 🔐 Security

- Firestore security rules enabled
- Authentication required before accessing chat
- Restricted storage access
- Token-based push notification handling

---

## 🧪 Testing (Recommended)

- Unit Testing
- Widget Testing
- Integration Testing
- Firebase Emulator Integration

---

## 🚀 Future Improvements

- ✅ Group Chats
- ✅ Voice Messages
- ✅ Video Calls
- ✅ Message Reactions
- ✅ End-to-End Encryption
- ✅ CI/CD Pipeline Integration

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a new feature branch
3. Commit changes with clear messages
4. Submit a Pull Request

---

## 📜 License

This project is licensed under the MIT License.

---

<div align="center">

## 👨‍💻 Developer

Abdallah Zaitoun  
Flutter Developer | Mobile Engineer

</div>
