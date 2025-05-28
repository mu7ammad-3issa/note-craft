# NoteCraft: A Flutter-Based Notes Application

NoteCraft is a simple yet powerful notes application built with Flutter. It allows users to create, manage, and customize their notes with different colors for better organization. All notes are stored locally on the device using Hive, ensuring your data is always accessible, even offline.

##  Screenshots


## Features ✨
![Screenshot_٢٠٢٥٠٥٢٨-٢٠٢٦٣٧](https://github.com/user-attachments/assets/9379699d-79b8-4022-89af-bc1bde4c9e92)
![Screenshot_٢٠٢٥٠٥٢٨-٢٠٢٦٤٣](https://github.com/user-attachments/assets/4402857b-a434-4020-9dcd-6949b05a577f)
![Screenshot_٢٠٢٥٠٥٢٨-٢٠٢٦٥٨](https://github.com/user-attachments/assets/2abfe54a-f10b-452d-8564-22e14247bcf8)
![Screenshot_٢٠٢٥٠٥٢٨-٢٠٢٧١٧](https://github.com/user-attachments/assets/b85c3907-0664-4bf7-aef7-715bfa59e028)


* **Create Notes**: Easily add new notes with a title and detailed content.
* **View & Edit Notes**: Access and modify your existing notes anytime.
* **Delete Notes**: Remove notes you no longer need.
* **Color Customization**: Assign unique colors to your notes for quick identification and visual appeal.
* **Local Storage**: Notes are saved securely on your device using Hive, a lightweight and fast NoSQL database.
* **Responsive Design**: A clean and user-friendly interface that works smoothly.
* **State Management**: Built with Flutter Bloc/Cubit for robust and maintainable state management.
* **Date Tracking**: Automatically saves the creation/modification date for each note.

## Technology Stack 🛠️

* **Framework**: Flutter
* **Programming Language**: Dart
* **State Management**: Flutter Bloc / Cubit
* **Local Database**: Hive
* **Icons**: Font Awesome Flutter
* **Date Formatting**: Intl

## Getting Started 🚀

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

* [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
* [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

### Prerequisites

* Flutter SDK: Make sure you have the Flutter SDK installed.
* Dart SDK: Included with Flutter.
* An IDE like Android Studio or VS Code with Flutter plugins.

### Installation & Setup

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/notecraft.git](https://github.com/your-username/notecraft.git) 
    # Replace with your actual repo URL
    cd notecraft
    ```

2.  **Install dependencies:**
    ```bash
    flutter pub get
    ```

3.  **Run the app:**
    ```bash
    flutter run
    ```

## Project Structure

The project follows a standard Flutter application structure:
notes_app/
├── android/                # Android specific files
├── ios/                    # iOS specific files
├── lib/
│   ├── cubits/             # Bloc/Cubit state management files
│   │   ├── add_note_cubit/
│   │   └── notes_cubit/
│   ├── models/             # Data models (e.g., NoteModel)
│   ├── views/              # UI screens/views
│   ├── widgets/            # Reusable UI components
│   ├── main.dart           # Main application entry point
│   └── constants.dart      # App-wide constants (colors, keys)
├── linux/                  # Linux specific files
├── macos/                  # macOS specific files
├── test/                   # Test files
├── web/                    # Web specific files
├── windows/                # Windows specific files
└── pubspec.yaml            # Project dependencies and metadata

## Contributing 🤝

Contributions are welcome! If you have ideas for improvements or find any bugs, feel free to open an issue or submit a pull request.

---
