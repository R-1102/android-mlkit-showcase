# ML Kit Showcase

An Android application designed to explore and demonstrate artificial intelligence and on-device machine learning capabilities using Google ML Kit.

Developed as a technical proof of concept during my professional experience to investigate practical AI integration in mobile applications.

The application brings together seven interactive machine learning features across Computer Vision and Natural Language Processing, using pre-trained models and a native Android interface built with Jetpack Compose.

## Features

### Computer Vision

- **Text Recognition (OCR):** Extract selectable text from images.
- **Barcode Scanning:** Detect and decode barcodes and QR codes.
- **Face Detection:** Detect and count faces within images.
- **Object Detection:** Detect and classify multiple objects within an image.

### Natural Language Processing

- **Language Identification:** Automatically identify the language of input text.
- **Text Translation:** Translate English text into Spanish using downloadable on-device language models.
- **Smart Reply:** Generate suggested responses through an interactive chat interface.

## Technologies

- Kotlin
- Android SDK
- Jetpack Compose
- Material 3
- Navigation Compose
- Google ML Kit
- Computer Vision
- Natural Language Processing
- On-device Machine Learning
- Gradle Kotlin DSL

## Project Structure

```text
app/
├── mainscreen/
├── vision/
│   ├── OCRScreen.kt
│   ├── BarcodeScreen.kt
│   ├── FaceScreen.kt
│   └── ObjectScreen.kt
└── naturalLanguage/
    ├── LanguageIDScreen.kt
    ├── TranslationScreen.kt
    └── SmartReplyChatScreen.kt
```

The application uses a feature-based structure, with dedicated Compose screens for each machine learning capability and centralized navigation.

## Getting Started

### Requirements

- Android Studio
- Android SDK 36
- Android device or emulator running API 24 or higher

### Installation

1. Clone the repository.
2. Open the project in Android Studio.
3. Sync Gradle dependencies.
4. Run the application on an Android device or emulator.
5. Select a machine learning feature from the home screen.

An internet connection may be required for the initial download of certain machine learning models.

## Project Purpose

This project explores practical mobile AI integration through pre-trained machine learning models, demonstrating how image analysis, language processing, and intelligent suggestions can be incorporated into native Android applications.
