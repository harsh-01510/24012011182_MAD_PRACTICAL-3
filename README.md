# 24012011182_MAD_PRACTICAL3

Mobile Application Development (MAD) Practical 3 - Android UI Layouts & Login Interface.

## 📌 Project Overview

This project is a native Android application developed in Kotlin using Android Studio. It demonstrates the implementation of Android user interface layouts, specifically working with `ConstraintLayout`, `CardView`, text fields (`EditText`), labels (`TextView`), buttons (`Button`), and image components (`ImageView`).

## 🚀 Features & Components

* **Main Screen (`MainActivity`)**: Displays a login/registration form enclosed within a rounded `CardView`.
  * **Logo Display**: `ImageView` rendering custom assets (`guni_pink_logo`).
  * **Input Fields**: `EditText` components for Email ID and Password entry.
  * **Submit Action**: Interactive `Button` for form submission.
* **Login Screen (`LoginActivity`)**: Secondary activity handling login workflow navigation.
* **Edge-to-Edge UI Support**: Modern window insets handling using `enableEdgeToEdge()` and `WindowInsetsCompat`.

## 📁 Project Structure

```text
24012011182_MAD_PRACTICAL3/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/example/a24012011182_mad_practical_3/
│   │   │   │   ├── MainActivity.kt
│   │   │   │   └── LoginActivity.kt
│   │   │   ├── res/
│   │   │   │   ├── layout/
│   │   │   │   │   ├── activity_main.xml
│   │   │   │   │   └── activity_login.xml
│   │   │   │   ├── drawable/
│   │   │   │   └── values/
│   │   │   └── AndroidManifest.xml
│   │   └── ...
│   └── build.gradle.kts
├── build.gradle.kts
└── settings.gradle.kts
```

## 🛠️ Prerequisites & Tools

* **IDE**: [Android Studio](https://developer.android.com/studio) (Ladybug / 2024.2+ or later recommended)
* **JDK**: Java 17 or higher
* **Min SDK**: API Level 24 (Android 7.0) or higher
* **Language**: Kotlin

## ⚙️ Building & Running

1. **Clone/Open Project**: Open Android Studio and select **File > Open**, then choose the project root folder.
2. **Gradle Sync**: Allow Android Studio to complete the Gradle sync.
3. **Run Application**:
   - Connect an Android device via USB debugging or start an Android Virtual Device (AVD) emulator.
   - Click the **Run** button (or press `Shift + F10`).
