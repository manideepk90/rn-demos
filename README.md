# React Native Demos

A collection of React Native demos showcasing various features, components, and implementations.

## 📱 About

This repository contains various React Native demo applications that demonstrate different concepts, features, and best practices for React Native development.

## 📂 Repository Structure

```
rn-demos/
├── demos/
│   ├── demo-name/
│   │   ├── App.js
│   │   ├── README.md
│   │   ├── package.json
│   │   └── screenshots/
│   └── ...
├── templates/
│   └── demo-template/
└── README.md
```

## 🚀 Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn
- React Native CLI or Expo CLI (depending on the demo)
- Android Studio / Xcode (for native builds)

### Running a Demo

Each demo is a standalone React Native project. To run a demo:

1. Navigate to the demo directory:
   ```bash
   cd demos/demo-name
   ```

2. Install dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```

3. Run the demo:
   ```bash
   # For Expo projects
   npm start
   # or
   npx expo start

   # For React Native CLI projects
   npm run android  # for Android
   npm run ios      # for iOS
   ```

## 📋 Available Demos

### 1. Hello World Demo
- **Path**: `demos/hello-world-demo`
- **Description**: A simple "Hello World" demo demonstrating the basic structure and setup
- **Key Features**: Basic React Native app structure, simple text display, minimal setup example

<!-- Add your demos here as you create them -->
<!-- Example:
### N. Demo Name
- **Path**: `demos/demo-name`
- **Description**: Brief description of what this demo showcases
- **Key Features**: List of key features demonstrated
-->

## ➕ Adding a New Demo

To add a new demo to this repository:

1. Create a new directory under `demos/` with a descriptive name
2. Initialize your React Native project in that directory
3. Add a README.md explaining what the demo showcases
4. Add screenshots in a `screenshots/` folder (if applicable)
5. Update this main README with a link to your demo

### Demo Structure Guidelines

Each demo should include:
- **README.md**: Description, features, and setup instructions
- **package.json**: Project dependencies
- **Source code**: Well-organized and commented code
- **Screenshots**: Visual representation of the demo (optional but recommended)

## 🤝 Contributing

Contributions are welcome! If you have a React Native demo you'd like to add:

1. Fork the repository
2. Create a new branch for your demo
3. Add your demo following the structure guidelines
4. Submit a pull request

## 📝 License

This project is open source and available for learning purposes.

## 📧 Contact

For questions or suggestions, please open an issue in this repository.