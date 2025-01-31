# Random Quotes Generator

A Flutter app that fetches and displays random quotes using a GET API. This project demonstrates API integration in Flutter and uses best practices for state management and UI updates.

## Features
- Fetch random quotes from an API
- Display the quote with a clean UI
- Refresh to get a new quote
- Simple and lightweight

## Technologies Used
- **Flutter**: UI development
- **Dart**: Programming language
- **http package**: API calls
- **Provider**: State management and dependency injection

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/random_quotes_generator.git
   ```
2. Navigate to the project folder:
   ```sh
   cd random_quotes_generator
   ```
3. Install dependencies:
   ```sh
   flutter pub get
   ```
4. Run the app:
   ```sh
   flutter run
   ```

## API Used
This app fetches quotes from an open API. Update the API URL in the code if needed.

## Project Structure
```
random_quotes_generator/
│-- lib/
│   │-- main.dart  # Entry point of the application
│   │-- provider/
│   │   ├── quote_provider.dart  # Manages state and provides data to the UI
│   │-- quotes_screen/
│   │   ├── quotes_screen.dart  # UI for displaying the quotes
│   │-- services/
│   │   ├── quote_service.dart  # Handles API calls
│-- pubspec.yaml  # Project dependencies
```

## Contributions
Feel free to fork this repository and submit pull requests to enhance functionality.

## License
This project is open-source and available under the [MIT License](LICENSE).

---
Happy coding! 🚀

