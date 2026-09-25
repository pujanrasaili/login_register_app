# Login & Registration App

A simple Flutter mobile UI for user Login and Registration, built as part of the Mobile Application Development (CIS099-2) coursework.

## Description

This project is a Flutter application with two screens — a Login page and a Registration page. It focuses on building the UI with common Flutter widgets, navigating between screens, and validating form input (email format, password length, matching confirm password, etc). There is no backend connected; it's a front-end UI exercise.

## Features

- Login page with email/username and password fields
- Show/Hide password toggle on the password field
- "Forgot Password?" option
- Navigation from Login to Registration and back
- Registration page with full name, email, password, and confirm password fields
- Form validation (empty fields, email format, minimum password length, password match)
- Simple, clean Material Design layout

## Screenshots

| Login Page | Registration Page |
|---|---|
|<img width="435" height="925" alt="Screenshot 2026-09-25 235935" src="https://github.com/user-attachments/assets/534a4bc0-192c-4ac9-8681-ab77f0a25f61" />|
 | <img width="452" height="917" alt="Screenshot 2026-09-25 235921" src="https://github.com/user-attachments/assets/43c2f073-47b5-4ad8-8aae-70e0200bf81b" />|

## Technologies Used

- Flutter
- Dart
- Android Studio
- Tested on: Pixel 7a (Android emulator/device)

## How to Run

1. Clone this repository
   ```
   git clone <your-repo-url>
   ```
2. Open the project folder in Android Studio (or VS Code)
3. Get the dependencies
   ```
   flutter pub get
   ```
4. Run the app on an emulator or connected device
   ```
   flutter run
   ```

## Project Structure

```
login_register_app/
├── lib/
│   ├── main.dart
│   └── pages/
│       ├── login_page.dart
│       └── register_page.dart
├── assets/
├── pubspec.yaml
└── README.md
```
