# Notie

A complete Flutter notes application with Firebase Authentication and Cloud Firestore integration using Provider for state management. Built as Individual Assignment 2 for ALU Flutter Mobile Development course.

## 🚀 Features

- **Separate Authentication Screens**: Dedicated Sign In and Sign Up screens
- **Firebase Authentication**: Email/Password signup and login with comprehensive validation
- **Real-time CRUD Operations**: Create, Read, Update, Delete notes with instant UI updates
- **Provider State Management**: Clean architecture eliminating all setState() calls
- **Real-time Firestore Sync**: Live data synchronization with Firestore database
- **Input Validation**: Comprehensive form validation with specific error messages
- **User Feedback**: Color-coded SnackBar notifications (green success, red error)
- **Clean UI**: Material Design 3 with responsive layouts and polished Cards
- **Session Persistence**: User stays logged in across app restarts
- **Error Handling**: Comprehensive error handling for all operations

## 📱 State Management - Provider Pattern

This app demonstrates advanced Provider usage with **zero setState() calls** in business logic:

## 🚀 Getting Started

### Prerequisites
- Flutter SDK (latest stable)
- Firebase CLI
- FlutterFire CLI

### Installation Steps
1. **Clone the repository**
   ```bash
   git clone [your-repo-url]
   cd flutter-notes-app-firebase
   ```

2. **Install dependencies**
   ```bash
   flutter pub get
   ```

3. **Firebase Configuration**
   ```bash
   npm install -g firebase-tools
   dart pub global activate flutterfire_cli
   flutterfire configure
   ```

5. **Run the application**
   ```bash
   flutter run
   ```