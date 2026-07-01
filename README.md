# Product Image Search - Object Detection

This Android application demonstrates how to use Google's ML Kit to detect and classify objects in images. It allows users to capture photos, select images from the gallery, or use preset sample images for detection.

## Features

- **Object Detection:** Detects multiple objects within an image using ML Kit.
- **Classification:** Provides labels for detected objects.
- **Camera Integration:** Capture real-time images for instant processing.
- **Gallery Support:** Pick existing images from the device gallery.
- **Preset Samples:** Includes sample images to quickly test detection capabilities.
- **Visual Feedback:** Draws bounding boxes and classification dots on the detected objects.

## Tech Stack

- **Kotlin:** Primary programming language.
- **ML Kit:** For object detection and classification.
- **Glide:** Efficient image loading and caching.
- **Volley:** Network operations (where applicable).
- **Gson:** JSON parsing.
- **View Binding:** Simplified UI component interaction.

## Project Configuration

- **Minimum SDK:** 23
- **Target SDK:** 35
- **Gradle Version:** 9.6.1
- **AGP Version:** 9.2.1

## Getting Started

1. **Clone the repository.**
2. **Open the project in Android Studio.**
3. **Ensure you have JDK 17 or higher** configured for Gradle in Android Studio settings.
4. **Build and run** the application on a physical device or emulator.

## How it Works

The core detection logic is handled in `ObjectDetectorActivity.kt`. It initializes an `ObjectDetector` with classification enabled. Images are converted into `InputImage` objects and processed asynchronously. The results are then visualized on an `ImageClickableView`.

---
*Copyright 2021 Google LLC*
