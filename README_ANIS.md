# 🎥 Anis App - أنيس

A social media platform for influencers to showcase content, similar to YouTube Kids with enhanced engagement features.

---

[![Flutter](https://img.shields.io/badge/Flutter-%5E3.0-blue?logo=flutter)](#)
[![Platforms](https://img.shields.io/badge/Platforms-Android%20%7C%20iOS-lightgrey)](#)
[![License](https://img.shields.io/badge/License-MIT-green)](#)
[![BLoC](https://img.shields.io/badge/BLoC-State_Management-blue)](#)

---

## 📸 Screenshots

<p align="center">
  <img src="screenshots/1.jpg" width="200" alt="Home Screen"/>
  <img src="screenshots/2.jpg" width="200" alt="Video Feed"/>
  <img src="screenshots/3.jpg" width="200" alt="Channel"/>
  <img src="screenshots/4.jpg" width="200" alt="Video Player"/>
</p>

<p align="center">
  <img src="screenshots/5.jpg" width="200" alt="Comments"/>
  <img src="screenshots/6.jpg" width="200" alt="Profile"/>
  <img src="screenshots/7.jpg" width="200" alt="Settings"/>
</p>

---

## ✅ Features

- ✓ Video upload and streaming for influencers
- ✓ Create and manage influencer profiles
- ✓ Follow/unfollow channels
- ✓ Like and dislike videos
- ✓ Voice recording for comments (STT)
- ✓ Real-time notifications (FCM)
- ✓ Video and audio player with caching
- ✓ Google Analytics integration
- ✓ Crash reporting (Sentry)
- ✓ User behavior tracking (SmartLook)
- ✓ Multi-flavor support (Dev, Staging, Production)
- ✓ Unit testing
- ✓ Clean Architecture with BLoC
- ✓ Responsive UI

---

## 🧰 Technology Stack

- Flutter (Mobile)
- Dart
- Firebase (Firestore, Auth, Storage, Analytics)
- FCM (Push Notifications)
- BLoC (State Management)
- Clean Architecture
- GetX / Go Router (Navigation)
- Sentry (Crash Reporting)
- SmartLook (User Analytics)
- Hive (Local Storage)

<p align="left">
  <img alt="Flutter" src="https://img.shields.io/badge/Flutter-%5E3.0-blue?logo=flutter" height="24" />
  <img alt="Dart" src="https://img.shields.io/badge/Dart-%5E2.0-blue?logo=dart" height="24" />
  <img alt="Firebase" src="https://img.shields.io/badge/Firebase-%5E9.0-yellow?logo=firebase" height="24" />
  <img alt="BLoC" src="https://img.shields.io/badge/BLoC-state_management-blue" height="24" />
</p>

---

## 🏛 Architecture

This project follows Clean Architecture with BLoC:

- **Presentation Layer:** Widgets, BLoC
- **Domain Layer:** Use cases, entities, repository interfaces
- **Data Layer:** Repository implementation, data sources (Firebase, Hive)
- **Core:** Utilities, constants, error handling

---

## 📦 Key Packages Used

- flutter_bloc — state management
- firebase_core, cloud_firestore, firebase_auth, firebase_storage, firebase_messaging, firebase_analytics — Firebase suite
- video_player — video playback
- just_audio — audio playback
- cached_network_image / cached_video_player — caching
- speech_to_text — voice comments
- go_router / get — navigation
- sentry_flutter — crash reporting
- google_analytics — analytics
- hive — local storage
- flutter_flavor — environment flavors

---

## 📲 Store Links

- **Play Store:** https://play.google.com/store/apps/details?id=com.Sikka_Plue.anees
- **App Store:** https://apps.apple.com/eg/app/%D8%A7%D9%86%D9%8A%D8%B3/id6476808032

---

## 🧾 License

This project is released under the MIT License.

---

## ✉️ Contact / Links

- **Name:** Ahmed Hussein
- **Email:** ahmed.dev229@gmail.com
- **LinkedIn:** https://www.linkedin.com/in/ahmed-hussein-66b1b71a5/
- **GitHub:** https://github.com/AhmedHussein22
- **Portfolio:** https://ahmed-portfolio-4ccaa.web.app/

---

Thank you for checking out Anis! 🎥
