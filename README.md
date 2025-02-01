

https://github.com/user-attachments/assets/324b61d6-d986-4936-a18d-bdd69f8e8553

# Taskey Manager

A **Task Management App** built using **Flutter**.

## Overview

Taskey is a feature-rich task management application designed to help users assign tasks, create teams, chat with team members, and manage tasks efficiently. We've also added a dark theme for enhanced user experience.

### Key Features:
- **Task Assignment:** Assign tasks to individual team members or groups.
- **Team Creation & Management:** Create teams, add members, and organize projects.
- **Real-time Team Chat:** Communicate with team members directly within the app.
- **Task Management:** Track progress, set deadlines, and manage tasks seamlessly.
- **Dark Theme:** Offers a smooth and user-friendly experience, especially in low-light environments.

### Technology Highlights:
- **State Management:** Utilizes **GetX** for efficient state and navigation management throughout the app.

## **Prerequisites**
Before starting, make sure you have the following installed:

1. **Flutter SDK**: [Install Flutter](https://flutter.dev/docs/get-started/install)
2. **Code Editor** (recommended: [Visual Studio Code](https://code.visualstudio.com/) or [Android Studio](https://developer.android.com/studio))
3. **Emulator or Physical Device**:
   - An Android/iOS emulator set up in Android Studio or Xcode.
   - A physical device with USB debugging enabled.

---

## **Steps to Run the Project**

### 1. **Clone or Download the Project**
If the project is hosted in a Git repository, clone it using:
```bash
git clone <REPO_URL>
cd <PROJECT_NAME>
```
## 2.  Verify Flutter Setup
```bash
flutter doctor
```

## 3. Install dependecies
```bash
Fluttler pub get
```

## 4. Select Device 
Ensure devices is available to run the app

## 5. Run the project
```bash
flutter run
```
## Packages Used:
- `firebase_core` for Firebase initialization
- `hooks_riverpod` for state management
- `cloud_firestore` for storing tasks in the cloud
- `firebase_auth` for user authentication
- `freezed_annotation` for data class generation
- `json_annotation` for JSON serialization
- `shared_preferences` for storing local user data
- `top_snackbar_flutter` for displaying snackbars
- `go_router` for route management
- `auto_route_generator` for code generation of routesoud
