
# My_SmolLM

## Overview

My_SmolLM is an Android application that brings the power of large language models (LLMs) to your mobile device, even older ones! By leveraging the open-source SmolChat-Android project's compiled JNI libraries, this app allows you to run GGUF format LLMs directly on your device without relying on cloud services. Enjoy private, offline conversations with an AI assistant in a lightweight, Java 6-compatible package.

## What Makes It Unique?

*   **Java 6 Compatibility:** Designed to run on a wide range of Android devices, including older ones that don't support modern Java features.
*   **Offline Functionality:** No internet connection is required once the model is loaded, ensuring your privacy and allowing use in areas with limited connectivity.
*   **Direct GGUF Model Support:** Utilizes the efficient GGUF format for LLMs, optimized for mobile devices.
*   **Based on SmolChat-Android:** Built using the solid foundation of the SmolChat-Android project, ensuring robust performance and compatibility.

## Features

*   **Model Selection:** Scan your device for compatible GGUF models.
*   **Chat Interface:** Engage in conversations with the loaded LLM.
*   **Clear Chat History:** Easily clear the conversation for a fresh start.
*   **System Prompt:** Set a custom system prompt to tailor the AI assistant's behavior.

## Getting Started

### Prerequisites

*   An Android device (API level 15 or higher).
*   A compatible GGUF format LLM file.

### Installation

1.  Download the APK file.
2.  Install the APK on your Android device. You may need to enable "Install from Unknown Sources" in your device settings.
3.  Place your GGUF model file in a known location on your device (e.g., the "Download" folder).

### Usage

1.  Launch the My_SmolLM application.
2.  Tap the "Scan for Models" button to search for GGUF files on your device.
3.  Select the desired model from the list.
4.  Once the model is loaded, you can start chatting!
5.  Type your message in the text field and tap the "Send" button.
6.  Use the "Clear Chat" button to clear the conversation history.

## Credits

This application utilizes the SmolChat-Android project's compiled JNI libraries. We thank the SmolChat-Android project and its contributors for their valuable work.

## License

This application is licensed under the Apache License 2.0. See the `LICENSE` file for more information.