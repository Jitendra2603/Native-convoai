# Reminder App 🔔

[![Flutter](https://img.shields.io/badge/Flutter-3.x-blue.svg)](https://flutter.dev/)
[![Firebase](https://img.shields.io/badge/Firebase-Latest-orange.svg)](https://firebase.google.com/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

A powerful Flutter-based reminder application with advanced AI capabilities, team collaboration features, and Firebase integration.


https://github.com/user-attachments/assets/5f5ef03b-3446-4dfa-89fd-a2730f8eec92


## ✨ Features

- 🤖 Task management with AI-powered suggestions
- 👥 Team collaboration tools
- 🗣️ Voice interactions using ElevenLabs
- 🔄 Real-time updates with Firebase
- 📱 Cross-platform support (Web, Android, iOS)
- 📅 Calendar integration
- ⭐ Priority management
- ✅ Task completion tracking

## 🚀 Prerequisites

- Flutter SDK (latest stable version)
- Firebase CLI
- Node.js and npm (for Firebase Functions)
- A Firebase project
- An ElevenLabs API key

## 🛠️ Setup Instructions

### 1. Initial Setup
```bash
# Clone the repository
git clone https://github.com/Jitendra2603/convoai-native.git
cd reminder-app

# Install dependencies
flutter pub get
```

### 2. Environment Setup ⚠️
1. Copy `.env.example` to `.env`
2. Copy `functions/.env.example` to `functions/.env`
3. Fill in your credentials:
   ```env
   ELEVENLABS_API_KEY=your_key_here
   FIREBASE_API_KEY=your_key_here
   # Add other required variables
   ```

### 3. Firebase Configuration ⚠️
- Create a new Firebase project
- Enable required services:
  - Authentication
  - Firestore
  - Cloud Functions
  - Storage
- Configure platform-specific files:
  - Android: `google-services.json`
  - iOS: `GoogleService-Info.plist`
  - Web: Firebase configuration in `index.html`


## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### Before Contributing:
- Ensure no sensitive data is included in your commits
- Run tests: `flutter test`
- Run analysis: `flutter analyze`
- Follow the [Flutter style guide](https://flutter.dev/docs/development/style-guide)

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE)
file for details.

