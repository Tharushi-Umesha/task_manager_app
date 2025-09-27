📱 Task Manager App
A simple yet powerful Flutter-based mobile application for managing daily tasks with a clean, intuitive interface.
<div align="center">
Show Image
Show Image
Show Image
</div>
✨ Features
Core Features (MVP)

✅ Add Tasks - Create new tasks with title and optional description
📋 Task List - View all your tasks in a clean, organized list
✔️ Mark Complete - Mark tasks as completed with visual feedback
🗑️ Delete Tasks - Remove tasks you no longer need
💾 Local Storage - All data stored locally using Hive database

Optional Features (Future Updates)

🏷️ Categories - Organize tasks by Work, Personal, Study, etc.
📅 Deadlines - Set due dates with date picker
📊 Dashboard - Overview of pending and completed tasks
🌙 Dark/Light Mode - Toggle between themes for better UX

🛠️ Tech Stack
TechnologyPurposeFlutter (Dart)Cross-platform UI frameworkHiveLightweight NoSQL local databaseProviderState management solutionMaterial DesignModern UI components
📂 Project Structure
task_manager_app/
├── lib/
│   ├── main.dart                 # App entry point
│   ├── models/
│   │   └── task.dart            # Task data model
│   ├── screens/
│   │   └── home_screen.dart     # Main app screen
│   ├── widgets/
│   │   └── task_tile.dart       # Individual task widget
│   └── providers/
│       └── task_provider.dart   # State management
├── pubspec.yaml                 # Dependencies
├── README.md                    # This file
└── screenshots/                 # App screenshots
🚀 Getting Started
Prerequisites

Flutter SDK (3.0.0 or higher)
Dart SDK (2.17.0 or higher)
Android Studio / VS Code
Android Emulator or Physical Device

Installation

Clone the repository

bash   git clone https://github.com/tharushiumesha/task_manager_app.git
   cd task_manager_app

Install dependencies

bash   flutter pub get

Run the app

bash   flutter run
Building for Release
Android APK:
bashflutter build apk --release
iOS (macOS only):
bashflutter build ios --release
📱 Screenshots
<div align="center">
Home ScreenAdd TaskCompleted TasksShow ImageShow ImageShow Image
Screenshots will be added after development
</div>
🎯 Usage

Adding a Task: Tap the floating action button and enter task details
Completing a Task: Tap the checkbox next to any task
Deleting a Task: Swipe left on a task or tap the delete icon
Viewing Tasks: All tasks are displayed on the main screen

🔧 Dependencies
yamldependencies:
  flutter:
    sdk: flutter
  hive: ^2.2.3
  hive_flutter: ^1.1.0
  provider: ^6.1.1
  path_provider: ^2.1.1

dev_dependencies:
  flutter_test:
    sdk: flutter
  hive_generator: ^2.0.1
  build_runner: ^2.4.7
  flutter_lints: ^3.0.1
🚧 Development Roadmap

 Basic task CRUD operations
 Local data persistence
 Task categories
 Due dates and reminders
 Task priority levels
 Search and filter functionality
 Data backup/restore
 Dark theme support

🤝 Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

Fork the project
Create your feature branch (git checkout -b feature/AmazingFeature)
Commit your changes (git commit -m 'Add some AmazingFeature')
Push to the branch (git push origin feature/AmazingFeature)
Open a Pull Request

📄 License
This project is licensed under the MIT License - see the LICENSE file for details.
👩‍💻 Author
Tharushi Umesha Mahipala

GitHub: https://github.com/Tharushi-Umesha
LinkedIn: [Tharushi Umesha Mahipala](https://www.linkedin.com/in/tharushi-umesha-mahipala-4b4b84280/)
Email: umemahee@gmail.com

🙏 Acknowledgments

Flutter team for the amazing framework
Hive team for the lightweight database solution
Material Design for the beautiful UI components


<div align="center">
⭐ Star this repository if you found it helpful!
Made with ❤️ by Tharushi Umesha Mahipala
</div>