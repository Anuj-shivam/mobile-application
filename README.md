# React Native Authentication App

This is a simple React Native application that provides **Sign Up** and **Login** functionality with proper form validation using **Formik** and **Yup**. It includes features like a **Remember Me** toggle for the Login form and a **Password Strength Indicator** for the Sign Up form.

## Features

- **Sign Up Form**:
  - Email and Password fields.
  - Password strength indicator (Weak, Medium, Strong).
  - Validates email format and password length.

- **Login Form**:
  - Email and Password fields.
  - "Remember Me" toggle saves the email to local storage.

- Accessibility:
  - ARIA roles and labels for better accessibility.

## Technologies Used

- **React Native**
- **TypeScript**
- **Formik** for form handling
- **Yup** for validation
- **AsyncStorage** for local storage
- **React Native CLI** for project setup

## Screenshots

_Add screenshots here if needed._

## How to Run the App

### Prerequisites
1. Install [Node.js](https://nodejs.org/) and npm (Node Package Manager).
2. Install React Native CLI globally:
   ```bash
   npm install -g react-native-cli
Running the App
Start the Metro bundler:
bash
Copy code
npx react-native start
Run the app on an emulator or connected device:
For Android:
bash
Copy code
npx react-native run-android
For iOS (MacOS only):
bash
Copy code
npx react-native run-ios
Project Structure
bash
Copy code
.
├── App.tsx         # Main application file with Sign Up and Login forms
├── package.json    # Project dependencies and scripts
├── tsconfig.json   # TypeScript configuration
├── node_modules/   # Installed dependencies
└── README.md       # Project documentation
Future Enhancements
Add server-side authentication (e.g., JWT-based login).
Include unit tests for the forms.
Improve UI/UX with animations and transitions.
Add dark mode support.
Contributing
Contributions are welcome! Feel free to open issues or submit pull requests to enhance this app.

License
This project is open-source and available under the MIT License.

sql
Copy code

