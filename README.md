<div align="center">

# 💬 ChatApp
### تطبيق دردشة فوري حديث | Modern Realtime Chat App

![Flutter](https://img.shields.io/badge/Flutter-3.x-blue?logo=flutter)
![Dart](https://img.shields.io/badge/Dart-3.x-blue?logo=dart)
![Firebase](https://img.shields.io/badge/Firebase-Backend-orange?logo=firebase)
![Platform](https://img.shields.io/badge/Platform-Android%20%7C%20iOS-green)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

تطبيق دردشة سريع، آمن، واحترافي صُمم لإظهار مهارات هندسة البرمجيات الحديثة.

</div>

---

## 📖 ملخص المشروع | Project Overview

ChatApp هو تطبيق مراسلة فورية، صُمم ليمنح تجربة استخدام سلسة وموثوقة على أجهزة Android و iOS.  
يدمج Flutter و Firebase لتقديم بنية قوية، واجهة حديثة، وأداء عالي في الوقت الحقيقي.

---

## ✨ المميزات | Key Features

- 🔐 تسجيل دخول آمن بالبريد الإلكتروني وكلمة المرور  
- 💬 دردشة فورية باستخدام Cloud Firestore  
- 🟢 حالة المستخدم (متصل / غير متصل)  
- 📷 مشاركة الصور عبر Firebase Storage  
- 🔔 إشعارات فورية عبر Firebase Cloud Messaging  
- 🌙 دعم الوضع الليلي  
- 📌 عرض آخر ظهور وتوقيت الرسائل  
- 🔍 البحث عن المستخدمين  
- 🗑️ حذف الرسائل  

---

## 🏗️ الهيكل المعماري | Architecture

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

**المبادئ المعمارية:**  
- فصل المسؤوليات (Separation of Concerns)  
- طبقة خدمات مستقلة للتعامل مع Firebase  
- إدارة حالة منظمة (Provider / Riverpod)  
- مكونات قابلة لإعادة الاستخدام  
- تنظيم الملفات بشكل احترافي  

---

## 🛠️ التقنيات المستخدمة | Tech Stack

| الطبقة | التقنية |
|--------|----------|
| واجهة المستخدم | Flutter |
| لغة البرمجة | Dart |
| المصادقة | Firebase Auth |
| قاعدة البيانات | Cloud Firestore |
| التخزين | Firebase Storage |
| الإشعارات | Firebase Cloud Messaging |

---

## ⚙️ التثبيت والتشغيل | Setup & Run

### 1️⃣ تحميل المشروع | Clone

```bash
git clone https://github.com/username/chatapp.git
cd chatapp
```

### 2️⃣ تثبيت المكتبات | Install Dependencies

```bash
flutter pub get
```

### 3️⃣ إعداد Firebase | Firebase Setup

1. إنشاء مشروع Firebase جديد  
2. تفعيل Authentication, Firestore, Storage, Cloud Messaging  
3. تحميل `google-services.json` ووضعه داخل `android/app/`  

### 4️⃣ تشغيل التطبيق | Run App

```bash
flutter run
```

---

## 🔐 الأمان | Security

- قواعد حماية Firestore  
- التحقق من المستخدم قبل الوصول للدردشة  
- تخزين مؤمن للصور والملفات  
- إدارة رموز الإشعارات بأمان  

---

## 🚀 خطط التطوير المستقبلي | Future Roadmap

- دردشات جماعية (Group Chat)  
- الرسائل الصوتية والفيديو  
- التفاعلات على الرسائل (Reactions)  
- تشفير كامل للمحادثات (End-to-End Encryption)  
- دمج CI/CD و Deployment آلي  

---

## 🤝 المساهمة | Contribution

1. عمل Fork للمشروع  
2. إنشاء فرع جديد  
3. تنفيذ التعديلات مع رسائل واضحة  
4. إرسال Pull Request  

---

## 📜 الترخيص | License

MIT License

---

<div align="center">

## 👨‍💻 المطور | Developer

Abdallah Zaitoun  
Flutter Developer | مهندس تطبيقات موبايل

</div>
