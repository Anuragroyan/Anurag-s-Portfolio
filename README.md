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

## Tech Stack
* Language: Kotlin
* UI: Jetpack Compose (Material 3)
* Architecture: MVVM
* State Management: Compose Runtime
* Backend: Firebase Authentication, Cloud Firestore, Firebase Storage
* Image Loading: Coil
* Android Libraries: AndroidX Core KTX, Lifecycle, Activity Compose
* Build Management: Compose BOM, Firebase BOM

## Architecture
The app is built using MVVM with a layered architecture:
* Presentation Layer: Jetpack Compose UI & ViewModels
* Domain Layer: Business logic and use cases
* Data Layer: Firebase repositories and data sources

## 💡 Challenges & Learnings
* Rebuilt a task management app that I originally developed three years ago in Java/XML, this time using Kotlin, Jetpack Compose, Material 3, and the latest Android development practices.
* Replaced custom XML implementations with official Android components such as Photo Picker, Date Picker, and Color Picker, resulting in a cleaner and more maintainable codebase.
* Redesigned the Firebase data structure and recreated the app’s core features while following an AI-assisted workflow for UI prototyping and implementing the business logic independently.
* The only pending enhancement is project-specific member visibility; currently, members are globally accessible, and I plan to refine the Firebase data model to support project-level access control.

- 📸 Screenshots/Demo
<img width="640" height="360" alt="2026-07-16 01-23-33" src="https://github.com/user-attachments/assets/a5eb3cc4-9808-4876-9a57-3af512a3239d" />

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

## Tech Stack
* Language: Kotlin
* UI: Jetpack Compose (Material 3)
* Architecture: MVVM
* Database: Firebase Cloud Firestore
* State Management: ViewModel & Compose State
* Android Libraries: AndroidX Core KTX, Lifecycle, Activity Compose
* Build Management: Compose BOM, Firebase BOM

## Architecture
The application follows the MVVM (Model–View–ViewModel) architecture to maintain a clear separation of concerns. ViewModel manages the UI state and 
Business logic, while Firebase Cloud Firestore serves as the data layer for storing and synchronizing notes, resulting in a scalable and maintainable application.

## 💡 Challenges & Learnings
* Implemented AndroidX Core KTX, Lifecycle, and Kotlin Coroutines to build a responsive, lifecycle-aware, and efficient application.
* Redesigned the UI to closely resemble a real notepad while creating a clean, modern, and intuitive user experience with Jetpack Compose.
* Structured the application using MVVM and integrated Firebase Cloud Firestore to deliver maintainable code and efficient CRUD operations.

- 📸 Screenshots/Demo
<img width="640" height="1138" alt="Notepad" src="https://github.com/user-attachments/assets/e779b764-20bd-431f-a59d-8d6d2197f6e8" />
  
 
  

