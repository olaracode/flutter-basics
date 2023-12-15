# Flutter Basics Project

This project is a basic Flutter application that demonstrates the use of several important concepts in Flutter development.

## Project Structure

1. **Main Function**: The entry point of the application. It calls the `runApp()` function with an instance of the `MyApp` widget.

2. **MyApp Widget**: This is a stateless widget that returns a `ChangeNotifierProvider` which creates an instance of `MyAppState`.

3. **MyAppState Class**: This class extends `ChangeNotifier` and manages the state of the application. It includes methods for generating random word pairs and managing a list of favorite word pairs.

4. **MyHomePage Widget**: This is a stateful widget that manages the current selected index for the navigation rail and displays the corresponding page.

5. **GeneratorPage and FavoritePage Widgets**: These are stateless widgets that display the current word pair and the list of favorite word pairs, respectively.

## Key Concepts

- **State Management**: This application uses the Provider package for state management. The `MyAppState` class extends `ChangeNotifier` and notifies listeners when the state changes.

- **Navigation**: The `NavigationRail` widget is used for navigating between the `GeneratorPage` and `FavoritePage`.

- **Use of Widgets**: The application makes extensive use of both stateless and stateful widgets, demonstrating the core concept of Flutter's widget-based architecture.

- **Use of Packages**: The application uses the `english_words` package to generate random word pairs.

## How to Run

To run this application, you need to have Flutter and Dart set up on your machine. Once you have these installed, you can run the application using the `flutter run` command in the terminal.
