# Anurag's Mobile App Portfolio

👋 Welcome!

Thank you for taking the time to explore my work.

This repository showcases the mobile applications I've built throughout my learning and professional journey. Instead of browsing through multiple repositories, you'll find my best Android, iOS, Flutter, and React Native projects organized in one place.

Each project includes:
- 📱 Overview
- ✨ Key Features
- 🛠️ Tech Stack
- 🏗️ Architecture
- 📸 Screenshots/Demo
- 🔗 Repository Link

---

# ⭐ Featured Projects

# 🖁 Android Projects

## <img width="50" height="50" alt="Kotlin" src="https://github.com/user-attachments/assets/2fde5ebb-5724-4f58-818a-264d9738f4f3" /> Projects 
 

## TeamTaskerManagerApp
- Overview:
A Trello-inspired task management app that helps users organize projects, assign tasks to team members, and track progress efficiently. Built with Firebase for authentication and real-time data management, it supports collaborative task planning with customizable task cards.

## Key Features:
* 🔐 User authentication (Login & Registration)
* ☁️ Firebase-powered backend and data storage
* ✅ Create, update, and manage tasks
* 👥 Add team members and assign tasks
* 🎨 Customize task cards with color selection
* ✏️ Edit and 🗑️ delete task cards
* 📋 Organize and track project progress collaboratively

## Tech Stack:
* Language: Kotlin
* UI: Jetpack Compose (Material 3)
* Architecture: MVVM
* State Management: Compose Runtime
* Backend: Firebase Authentication, Cloud Firestore, Firebase Storage
* Image Loading: Coil
* Android Libraries: AndroidX Core KTX, Lifecycle, Activity Compose
* Build Management: Compose BOM, Firebase BOM

## Architecture:
The app is built using MVVM with a layered architecture:
* Presentation Layer: Jetpack Compose UI & ViewModels
* Domain Layer: Business logic and use cases
* Data Layer: Firebase repositories and data sources

## 💡 Challenges & Learnings:
* Rebuilt a task management app that I originally developed three years ago in Java/XML, this time using Kotlin, Jetpack Compose, Material 3, and the latest Android development practices.
* Replaced custom XML implementations with official Android components such as Photo Picker, Date Picker, and Color Picker, resulting in a cleaner and more maintainable codebase.
* Redesigned the Firebase data structure and recreated the app’s core features while following an AI-assisted workflow for UI prototyping and implementing the business logic independently.
* The only pending enhancement is project-specific member visibility; currently, members are globally accessible, and I plan to refine the Firebase data model to support project-level access control.

## 📸 Screenshots/Demo:
<img width="640" height="1436" alt="Teamtasker" src="https://github.com/user-attachments/assets/dd31f014-caf0-4a62-b784-04ec2215fd69" />


## NotepadApp
- Overview
A modern note-taking application that enables users to create, read, update, and delete notes with ease. It supports color-coded notes using customizable
Hex colors make information more organized and visually accessible.

## Key Features:
* 📝 Create, view, update, and delete notes (CRUD operations)
* 🎨 Assign custom hex colors to notes
* 🔍 View all notes in a clean and organized layout
* 📌 Edit existing notes with real-time updates
* 🗑️ Delete notes with ease
* 📱 Modern and responsive UI built with Jetpack Compose

## Tech Stack:
* Language: Kotlin
* UI: Jetpack Compose (Material 3)
* Architecture: MVVM
* Database: Firebase Cloud Firestore
* State Management: ViewModel & Compose State
* Android Libraries: AndroidX Core KTX, Lifecycle, Activity Compose
* Build Management: Compose BOM, Firebase BOM

## Architecture:
The application follows the MVVM (Model–View–ViewModel) architecture to maintain a clear separation of concerns. ViewModel manages the UI state and Business logic, while Firebase Cloud Firestore serves as the data layer for storing and synchronizing notes, resulting in a scalable and maintainable application.

## 💡 Challenges & Learnings:
* Implemented AndroidX Core KTX, Lifecycle, and Kotlin Coroutines to build a responsive, lifecycle-aware, and efficient application.
* Redesigned the UI to closely resemble a real notepad while creating a clean, modern, and intuitive user experience with Jetpack Compose.
* Structured the application using MVVM and integrated Firebase Cloud Firestore to deliver maintainable code and efficient CRUD operations.

## 📸 Screenshots/Demo:
<img width="640" height="1138" alt="Notepad" src="https://github.com/user-attachments/assets/e779b764-20bd-431f-a59d-8d6d2197f6e8" />
  
 ## Offline BankApp
- Overview:
A modern offline banking application that helps users create and manage bank accounts while tracking debit and credit transactions.
It also supports data reset and JSON export, providing a simple and efficient way to manage financial records locally.

## Key Features:
* 🏦 Create and manage multiple bank accounts
* 💸 Record debit and credit transactions
* 📝 Store transaction details with account history
* 📊 View organized transaction records
* 📴 Fully offline functionality with local data storage
* 🔄 Reset all application data when required
* 📄 Export transaction data in JSON format
* 📱 Clean and intuitive Jetpack Compose UI

## Tech Stack:
* Language: Kotlin
* UI: Jetpack Compose (Material 3)
* Architecture: MVVM
* State Management: ViewModel & Compose State
* Serialization: Kotlinx Serialization (JSON)
* Android Libraries: AndroidX Core KTX, Lifecycle, Activity Compose, Foundation
* Build Management: Compose BOM

## Architecture:
The application follows the MVVM (Model–View–ViewModel) architecture to separate the UI, business logic, and data layers. ViewModel manages the application state, while the local data layer handles offline storage and JSON serialization, resulting in a scalable, maintainable, and responsive application.

## 💡 Challenges & Learnings:
* Implemented Kotlin Serialization to export and manage transaction data efficiently in JSON format.
* Applied the Repository Pattern to separate data handling from business logic, improving code maintainability and scalability.
* Implemented a custom ViewModel Factory for proper ViewModel initialization and lifecycle-aware state management.

## 📸 Screenshots/Demo:
<img width="640" height="1138" alt="BankinApp" src="https://github.com/user-attachments/assets/1ba84165-0242-4c8f-9205-8e8c880a95cf" />
