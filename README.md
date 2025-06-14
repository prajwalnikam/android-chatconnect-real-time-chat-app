# 💬 Chatoon – Real-Time Chat Application with Firebase & Jetpack Compose

---

## 📌 Project Description

Chatoon is a modern, real-time chat application built for Android using *Jetpack Compose* and *Firebase*. It enables users to register, log in, create chat rooms, and exchange messages instantly. The app leverages Firebase Authentication, Firestore, and Cloud Messaging to deliver a seamless and secure chatting experience.

---

## 🖼 Output Screenshots

### Authentication
![Login/Register](https://your-screenshot-link/login.png)

### Chat Room List
![Chat Rooms](https://your-screenshot-link/chatrooms.png)

### Messaging
![Chat](https://your-screenshot-link/chat.png)

---

## 🛠 Technologies Used

- *Kotlin* (Android)
- *Jetpack Compose* (UI)
- *Firebase Authentication* (User Management)
- *Firebase Firestore* (Real-Time Database)
- *Firebase Cloud Messaging* (Push Notifications)
- *Material 3* (UI Components)

---

## 🧩 Project Structure


Chatoon/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/example/myapplication/
│   │   │   │   ├── view/...
│   │   │   │   ├── nav/...
│   │   │   │   ├── ui/theme/...
│   │   │   │   ├── Constants.kt
│   │   │   │   ├── MainActivity.kt
│   │   │   │   ├── NavComposeApp.kt
│   │   │   ├── res/
│   │   │   │   ├── drawable/
│   │   │   │   ├── layout/
│   │   │   │   └── values/
│   ├── build.gradle
│   ├── google-services.json
├── functions/ (Firebase Cloud Functions)
│   ├── index.js
│   └── ...
├── build.gradle
├── settings.gradle
└── README.md


---

## ⚙ Installation & Setup

### Prerequisites

- Android Studio (Flamingo or newer)
- Firebase Project (with Authentication, Firestore, and Cloud Messaging enabled)

### Steps

1. *Clone the repository:*
    bash
    git clone https://github.com/yourusername/Chatoon.git
    cd Chatoon/app
    

2. *Add your Firebase config:*
    - Download google-services.json from your Firebase Console and place it in app/.

3. *Build the project:*
    - Open in Android Studio and sync Gradle.

4. *Run the app:*
    - Connect an Android device or use an emulator.
    - Click *Run*.

---

## 🚀 Features

- User Registration & Login (with validation)
- Create and join chat rooms
- Real-time messaging with sender display
- Push notifications for new messages
- Responsive Material 3 UI
- Password strength & confirmation checks

---

## 🔒 Security & Best Practices

- Passwords are validated for strength and confirmed before registration.
- User data is stored securely in Firestore.
- Push notifications use FCM topics per chat room.

---

## 📝 How to Use

1. *Register* a new account or *log in*.
2. *Create* a chat room or *join* an existing one.
3. *Send messages* in real time and receive notifications.

---

## 📂 Firebase Cloud Functions

- Located in [functions/index.js](functions/index.js)
- Sends push notifications to users subscribed to chat room topics.

---

## 📄 License

This project is licensed under the MIT License.

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

---

## Contact

For questions or support, please contact [your.email@example.com](mailto:your.email@example.com).