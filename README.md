# React Native Starter App

A starter React Native application with basic project structure and navigation setup.

## Features

- TypeScript support
- React Navigation integration
- Basic screen structure
- Clean project setup

## Getting Started

### Prerequisites

- Node.js (version 16 or newer)
- npm or yarn
- React Native development environment (follow the [official guide](https://reactnative.dev/docs/environment-setup))

### Installation

1. Clone this repository
   ```bash
   git clone https://github.com/EloGamerr/react-native-starter-app.git
   cd react-native-starter-app
   ```

2. Install dependencies
   ```bash
   npm install
   # or
   yarn
   ```

3. For iOS, install pods (if developing for iOS)
   ```bash
   cd ios && pod install && cd ..
   ```

### Running the App

#### For iOS:

```bash
npm run ios
# or
yarn ios
```

#### For Android:

```bash
npm run android
# or
yarn android
```

## Project Structure

```
react-native-starter-app/
├── App.tsx              # Main application component
├── index.js             # Entry point
├── src/                 # Source files
│   ├── screens/         # Screen components
│   │   ├── HomeScreen.tsx
│   │   └── DetailsScreen.tsx
├── package.json         # Project dependencies
└── README.md            # Project documentation
```

## Built With

- [React Native](https://reactnative.dev/) - The framework used
- [React Navigation](https://reactnavigation.org/) - Navigation library

## Adding Native Code

If you're developing a new feature that requires native code, follow these steps:

1. Run the following command to generate the native folders if they don't exist:
   ```bash
   npx react-native init NameOfYourNativeProject
   ```

2. Copy the iOS and Android folders from the newly created project to your project

## License

This project is licensed under the MIT License