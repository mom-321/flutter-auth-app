# Firebase Authentication Flutter App

This is a Flutter app that demonstrates Firebase authentication, allowing users to sign up and log in using their email and password.

## Features

- User authentication via email and password
- Firebase integration for user sign-in and sign-up
- Simple UI for login and signup pages

## Setup

### Prerequisites

- Flutter SDK (ensure you have it installed on your system)
- Firebase account
- Firebase project created with authentication enabled

### Steps to run the app

1. **Clone the repository:**
   Open your terminal and run:
   ```bash
   git clone https://github.com/username/flutter-auth-app.git
In main.dart, Firebase is initialized with the following configuration:

dart
Copy
Edit
await Firebase.initializeApp(
  options: const FirebaseOptions(
    apiKey: "your-api-key",
    authDomain: "your-auth-domain",
    projectId: "your-project-id",
    storageBucket: "your-storage-bucket",
    messagingSenderId: "your-messaging-sender-id",
    appId: "your-app-id",
  ),
);
Replace "your-api-key", "your-auth-domain", etc., with the actual configuration from the Firebase Console.
