# Contributing to React Native Demos

Thank you for your interest in contributing to the React Native Demos repository! This guide will help you add your own demos to the collection.

## 📋 Before You Start

- Make sure your demo is working and tested
- Ensure your code is clean and well-commented
- Check that your demo doesn't duplicate existing content

## ✅ How to Add a Demo

### Step 1: Fork and Clone

1. Fork this repository
2. Clone your fork locally:
   ```bash
   git clone https://github.com/YOUR_USERNAME/rn-demos.git
   cd rn-demos
   ```

### Step 2: Create Your Demo

1. Create a new directory for your demo under `demos/`:
   ```bash
   mkdir demos/your-demo-name
   cd demos/your-demo-name
   ```

2. Initialize your React Native project:
   ```bash
   # Using Expo
   npx create-expo-app . --template blank

   # Or using React Native CLI
   npx react-native init YourDemoName .
   ```

3. Develop your demo with clear, well-commented code

### Step 3: Document Your Demo

1. Create a README.md in your demo directory using the template from `templates/demo-template/README.md`
2. Include:
   - Clear description of what the demo showcases
   - Installation and running instructions
   - List of features and concepts demonstrated
   - Screenshots or GIFs (if applicable)

3. Create a `screenshots/` folder if you have visual content:
   ```bash
   mkdir screenshots
   ```

### Step 4: Update Main README

Add your demo to the "Available Demos" section in the main README.md:

```markdown
### N. Your Demo Name
- **Path**: `demos/your-demo-name`
- **Description**: Brief description
- **Key Features**: List of features
```

### Step 5: Test Your Demo

1. Make sure your demo runs without errors:
   ```bash
   cd demos/your-demo-name
   npm install
   npm start
   ```

2. Test on both iOS and Android if possible

### Step 6: Submit Your Contribution

1. Commit your changes:
   ```bash
   git add .
   git commit -m "Add: Your Demo Name - brief description"
   ```

2. Push to your fork:
   ```bash
   git push origin main
   ```

3. Create a Pull Request from your fork to the main repository

## 📝 Demo Guidelines

### Code Quality

- Write clean, readable code
- Add comments explaining complex logic
- Follow React Native best practices
- Use meaningful variable and function names

### Structure

Each demo should include:
- `README.md` - Documentation
- `package.json` - Dependencies
- Source code files
- `screenshots/` folder (optional but recommended)

### README Template

Use the template provided in `templates/demo-template/README.md` as a starting point.

### Naming Conventions

- Use lowercase with hyphens for directory names: `my-awesome-demo`
- Be descriptive but concise
- Avoid generic names like "test" or "example"

## 🎯 Demo Ideas

Need inspiration? Here are some demo ideas:

- Navigation patterns (Tab, Drawer, Stack)
- Animation examples
- State management (Redux, Context, MobX)
- API integration and data fetching
- Custom components (buttons, cards, forms)
- Camera and media handling
- Geolocation features
- Authentication flows
- Offline storage
- Gesture handling
- Dark mode implementation
- Responsive layouts

## ❓ Questions?

If you have questions or need help, please:
- Open an issue in the repository
- Check existing demos for reference
- Review React Native documentation

## 🙏 Thank You!

Your contributions help others learn React Native. Thank you for sharing your knowledge!
