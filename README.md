# Expense Tracker

A Flutter-based expense tracker application that allows users to manage their expenses efficiently. This project is part of the **"A Complete Guide to the Flutter SDK & Flutter Framework for building native iOS and Android apps"** course on Udemy.

## Features

- Add, view, and delete expenses.
- Categorize expenses into predefined categories (e.g., Food, Travel, Leisure, Work).
- View expenses in a chart for better visualization.
- Undo expense deletion using a Snackbar.

## Project Structure

The project is organized as follows:

```
lib/
├── models/
│   └── expense.dart           # Expense model and related logic
├── widgets/
│   ├── chart/                 # Chart widget for expense visualization
│   ├── expenses_list/         # List widget for displaying expenses
│   ├── new_expense.dart       # Widget for adding new expenses
│   └── expenses.dart          # Main widget for managing expenses
```

## Getting Started

### Prerequisites

- Install [Flutter](https://flutter.dev/docs/get-started/install) on your system.
- Ensure you have an IDE like [Visual Studio Code](https://code.visualstudio.com/) or [Android Studio](https://developer.android.com/studio).

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/expense_tracker.git
   cd expense_tracker
   ```
2. Install dependencies:
   ```sh
    flutter pub get
   ```
3. Run the app:
   ```sh
    flutter run
   ```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Resources

- [Flutter](https://flutter.dev)
- [Udemy Course](https://www.udemy.com/course/learn-flutter-dart-to-build-ios-android-apps)
