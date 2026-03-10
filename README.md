# 🔥 TP Firebase - Flutter

A Flutter mobile application integrating Firebase Authentication and Cloud Firestore, built as part of a Mobile Development lab at USTHB.

## 📱 Features

- **Sign Up** — Register with first name, last name, date of birth, email and password
- **Login** — Authenticate with email and password
- **Profile** — View your profile data stored in Firestore
- **Logout** — Sign out of your account
- **Password Reset** — Receive a password reset email

## 🛠️ Tech Stack

- [Flutter](https://flutter.dev/)
- [Firebase Authentication](https://firebase.google.com/docs/auth)
- [Cloud Firestore](https://firebase.google.com/docs/firestore)

## 📁 Project Structure

```
lib/
├── main.dart              # App entry point + ProfilePage
├── auth_service.dart      # Firebase Auth & Firestore logic
├── login_page.dart        # Login screen
├── signup_page.dart       # Signup screen
├── reset_password.dart    # Password reset screen
└── firebase_options.dart  # Firebase configuration (auto-generated)
```

## 🚀 Getting Started

### Prerequisites

- Flutter SDK
- A Firebase project with Authentication (Email/Password) and Firestore enabled

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/YOUR_USERNAME/tp-firebase.git
   cd tp-firebase
   ```

2. **Install dependencies**
   ```bash
   flutter pub get
   ```

3. **Configure Firebase**
   ```bash
   flutterfire configure
   ```

4. **Run the app**
   ```bash
   flutter run
   ```

## ⚙️ Firebase Setup

1. Create a project on [Firebase Console](https://console.firebase.google.com/)
2. Enable **Email/Password** in Authentication → Sign-in method
3. Create a **Firestore Database** in test mode
4. Add an Android app with package name `com.tp.firebase`
5. Download `google-services.json` and place it in `android/app/`

## 🎥 Demo

[Watch the demo video](https://drive.google.com/drive/folders/1zS4u9YMISSec5pPGO9W0MLB9xTZlLQoM?usp=sharing)

## 👩‍💻 Author

Developed as part of the Mobile Development course — Département Informatique, USTHB.
