# Installation Guide

This document provides clear, technical instructions for developers to reproduce the CluckTalk environment.

## Prerequisites

To build and run CluckTalk from source, ensure you have the following installed:

- **Flutter SDK:** Version 3.22.0 or higher
- **Dart SDK:** Version 3.4.3 up to 4.0.0

## Setup Instructions

1. Clone the repository:

   ```bash
   git clone https://github.com/mooanalytica/Clucktalk
   ```

2. Navigate to the project directory:

   ```bash
   cd Clucktalk
   ```

3. Install dependencies:

   ```bash
   flutter pub get
   ```

4. Run the application:

   Ensure an Android emulator or iOS simulator is running, then execute:

   ```bash
   flutter run
   ```

## Notes

- If you are on macOS and developing for iOS, you may need to run `pod install` inside the `ios` directory.
- For Android development, ensure Android SDK and emulator tools are configured in your PATH.
