
![Perdasi Store](https://github.com/user-attachments/assets/08d3704d-e502-4174-851c-eb459acaedba)


# 🛍️ Perdasi Store

**Perdasi Store** is a modern and responsive eCommerce mobile application built using Flutter and Dart. It integrates Firebase backend services for authentication and database operations, applies MVVM clean architecture, and utilizes Riverpod for state management. This application is designed to deliver a seamless shopping experience with persistent session handling and real-time updates.


---

## Features

- Clean and scalable **MVVM architecture**
- **Firebase Authentication** with secure login and signup
- **Cloud Firestore** integration for product and user data storage
- Real-time **state management** using **Riverpod**
- **SharedPreferences** for user session persistence
- **Push notifications** for user engagement
- Responsive UI compatible with all device sizes
- Structured folder organization and reusable widgets

---

## Tech Stack

- **Flutter** & **Dart**
- **Riverpod** (state management)
- **Firebase Auth**
- **Cloud Firestore**
- **Firebase Cloud Messaging (FCM)**
- **SharedPreferences**
- **MVVM (Model-View-ViewModel)** pattern

## Screens

![Perdasi Store Screens](https://github.com/user-attachments/assets/bf959624-10d8-4032-8fd9-6edf8d0ac1b4)


---

## Folder Structure


lib/
├── binding/
├── common/
│ ├── style/
│ └── widgets/
├── data/
│ ├── repositories/
│ └── services/
├── features/
│ ├── auth/
| |   ├── controllers/
│ |   ├── models/
│ |   └── screens/
│ ├── personalization/
| |   ├── controllers/
│ |   ├── models/
│ |   └── screens/
│ └── shop/
| |   ├── controllers/
│ |   ├── models/
│ |   └── screens/
├── localization/
├── utils/
│ ├── constant/
│ ├── devices/
│ ├── formatters/
│ ├── helpers/
│ ├── http/
│ ├── local-storage/
│ ├── logging/
│ ├── theme/
│ └── validators/
└── main.dart



