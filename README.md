# Aarohi Edge Detection Viewer

This project is implemented by **Aarohi** as part of a real-time Android + OpenCV-C++ + OpenGL + Web (TypeScript) R&D assignment.

## Overview

- Captures live camera frames on Android
- Sends frames to native C++ via JNI
- Uses OpenCV (C++) for edge detection / grayscale
- Renders processed frames with OpenGL ES 2.0
- Includes a minimal `/web` TypeScript viewer to display a processed sample frame with basic stats

## Tech Stack

- **Android**: Kotlin, Camera API, TextureView
- **Native**: C++17, OpenCV, JNI, NDK
- **Rendering**: OpenGL ES 2.0
- **Web**: TypeScript + HTML

## Project Structure

- `/app` – Android app (camera + UI glue)
- `/app/src/main/cpp` – Native C++ (OpenCV processing)
- `/app/src/main/java` – Camera + JNI bridge + GL renderer
- `/web` – TypeScript web viewer for processed frames
