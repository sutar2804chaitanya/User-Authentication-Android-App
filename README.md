# 🔐 User Authentication Android App

A simple Android application developed using **Java**, **XML**, and **Android Studio** that provides user registration, login authentication, and dashboard access. The application stores user information locally using **SharedPreferences** and demonstrates basic Android authentication workflows.

## 📖 Project Overview

This project was developed as part of the **Mobile Application Development** course to demonstrate user registration, login verification, local data storage, and multi-activity navigation in Android.

Users can create an account, log in using registered credentials, access a personalized dashboard, and log out securely.

## 🎯 Aim

To develop an Android application that:

* Allows users to register with personal details.
* Stores user data using SharedPreferences.
* Authenticates users through a login screen.
* Displays a personalized dashboard after successful login.
* Demonstrates activity navigation and local data persistence.

## ✨ Features

* User Registration Form
* Login Authentication
* Dashboard Screen
* Welcome Message with User Name
* Logout Functionality
* SharedPreferences Data Storage
* Intent-Based Navigation
* Simple and User-Friendly Interface
* Lightweight Android Application

## 🛠️ Technologies Used

| Technology        | Purpose                 |
| ----------------- | ----------------------- |
| Java              | Application Logic       |
| XML               | User Interface Design   |
| Android Studio    | Development Environment |
| Android SDK       | Android Framework       |
| SharedPreferences | Local Data Storage      |
| Intent            | Activity Navigation     |

## 📂 Project Structure

```text
User-Authentication-Android-App/
│
├── app/
│   ├── src/main/
│   │
│   ├── java/com/example/assignment5/
│   │   ├── RegistrationActivity.java
│   │   ├── loginActivity.java
│   │   └── dashboard.java
│   │
│   ├── res/layout/
│   │   ├── activity_main.xml
│   │   ├── activity_login.xml
│   │   └── activity_dashboard.xml
│   │
│   └── AndroidManifest.xml
│
└── README.md
```

## ⚙️ Application Workflow

### Registration Screen

The user enters:

* Name
* Email Address
* Password
* Phone Number

After clicking **Register**:

* User details are saved in SharedPreferences.
* User is redirected to the Login Screen.

### Login Screen

The user enters:

* Registered Email
* Registered Password

The application verifies the credentials with stored data.

### Dashboard Screen

After successful login:

* User is welcomed with a personalized message.
* Dashboard screen is displayed.
* Logout option is available.

### Logout

When the user clicks Logout:

* The dashboard closes.
* User returns to the Login Screen.

## 📸 Screenshots

### Registration Page

* Name field
* Email field
* Password field
* Phone Number field
* Register button

### Login Page

* Email field
* Password field
* Login button

### Dashboard Page

* Welcome message
* Logout button

> Add application screenshots in a `screenshots` folder and update this section.

## 🧠 Concepts Implemented

* Android Activities
* SharedPreferences
* Intent Navigation
* EditText
* TextView
* Button Click Events
* User Authentication
* Data Persistence
* Activity Lifecycle
* Form Handling
* Toast Messages
* Session Management Basics

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/User-Authentication-Android-App.git
```

2. Open the project in Android Studio.

3. Sync Gradle files.

4. Connect an Android device or launch an emulator.

5. Click **Run** ▶️.

## 📚 Learning Outcomes

Through this project, the following concepts were learned:

* Android User Interface Design
* User Registration and Login Workflow
* SharedPreferences for Data Storage
* Intent-Based Activity Navigation
* Handling User Inputs
* Authentication Logic
* Building Multi-Screen Android Applications

## 🔮 Future Enhancements

* Password Encryption
* Forgot Password Functionality
* Profile Management
* Remember Me Option
* SQLite Database Integration
* Firebase Authentication
* Biometric Login Support
* Dark Mode Support
* Material Design Components

##
