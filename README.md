# Todo List App (Expo/React Native)

A premium, production-ready Todo List application built with Expo and React Native. This project features a clean architecture, persistent local storage, and high accessibility standards.

## ✨ Features

- **Persistent Storage**: Uses `@react-native-async-storage/async-storage` to ensure your tasks survive app reloads.
- **Modern UI/UX**: Clean, card-based design with subtle shadows, custom components, and dedicated empty states.
- **Accessibility**: Optimized for screen readers with proper ARIA labels and roles.
- **Clean Architecture**: Centralized types and custom hooks (`useTodos`) for maintainable state management.
- **Robustness**: UUID-based task identification and basic error handling.

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (LTS recommended)
- [Expo Go](https://expo.dev/go) app on your mobile device OR an Android/iOS emulator.

### Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd todo-list-app-main
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the project:
   ```bash
   npx expo start
   ```

4. Scan the QR code with your Expo Go app (Android) or Camera app (iOS) to run the project.

## 🛠️ Tech Stack

- **Framework**: [Expo](https://expo.dev/) / [React Native](https://reactnative.dev/)
- **Navigation**: [Expo Router](https://docs.expo.dev/router/introduction/)
- **Persistence**: [AsyncStorage](https://react-native-async-storage.github.io/async-storage/)
- **Styling**: Vanilla React Native `StyleSheet`

## 📝 Standards Compliance

This project follows strict architectural and accessibility standards:
- **DRY Principle**: Shared types and logic.
- **Accessibility**: WCAG 2.1 aligned (ARIA labels, roles).
- **Security**: No hardcoded secrets, robust ID generation.

## 📄 License

MIT
