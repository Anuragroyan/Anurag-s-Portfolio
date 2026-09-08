Anurag’s Mobile App Portfolio

👋 Welcome!

Thank you for taking the time to explore my work.

This repository showcases the mobile applications I’ve built throughout my learning and professional journey. Instead of browsing through multiple repositories, you’ll find my best Android, iOS, Flutter, and React Native projects organized in one place.

Each project includes:

* 📱 Overview
* ✨ Key Features
* 🛠️ Tech Stack
* 🏗️ Architecture
* 💡 Challenges & Learnings
* 📸 Screenshots/Demo
* 🔗 Repository Link

⸻

⭐ Featured Projects

🖁 Android Projects

<img width="100" height="100" alt="Kotlin" src="https://github.com/user-attachments/assets/79dbc14d-1218-46ae-a627-3135b4c5fa79" />

TeamTaskerManagerApp

📱 Overview

A Trello-inspired task management app that helps users organize projects, assign tasks to team members, and track progress efficiently. Built with Firebase for authentication and real-time data management, it supports collaborative task planning with customizable task cards.

✨ Key Features

* 🔐 User authentication (Login & Registration)
* ☁️ Firebase-powered backend and data storage
* ✅ Create, update, and manage tasks
* 👥 Add team members and assign tasks
* 🎨 Customize task cards with color selection
* ✏️ Edit and 🗑️ delete task cards
* 📋 Organize and track project progress collaboratively

🛠️ Tech Stack

* Language: Kotlin
* UI: Jetpack Compose (Material 3)
* Architecture: MVVM
* State Management: Compose Runtime
* Backend: Firebase Authentication, Cloud Firestore, Firebase Storage
* Image Loading: Coil
* Android Libraries: AndroidX Core KTX, Lifecycle, Activity Compose
* Build Management: Compose BOM, Firebase BOM
* Version Control: Git & GitHub

🏗️ Architecture

The app is built using MVVM with a layered architecture:

* Presentation Layer: Jetpack Compose UI & ViewModels
* Domain Layer: Business logic and use cases
* Data Layer: Firebase repositories and data sources

💡 Challenges & Learnings

* Rebuilt a task management app that I originally developed three years ago in Java/XML, this time using Kotlin, Jetpack Compose, Material 3, and the latest Android development practices.
* Replaced custom XML implementations with official Android components such as Photo Picker, Date Picker, and Color Picker, resulting in a cleaner and more maintainable codebase.
* Redesigned the Firebase data structure and recreated the app’s core features while following an AI-assisted workflow for UI prototyping and implementing the business logic independently.
* The only pending enhancement is project-specific member visibility; currently, members are globally accessible, and I plan to refine the Firebase data model to support project-level access control.

📸 Screenshots/Demo

<img width="640" height="1438" alt="Teamtasker" src="https://github.com/user-attachments/assets/dd31f014-caf0-4a62-b784-04ec2215fd69" />

⸻

NotepadApp

📱 Overview

A modern note-taking application that enables users to create, read, update, and delete notes with ease. It supports color-coded notes using customizable Hex colors, making information more organized and visually accessible.

✨ Key Features

* 📝 Create, view, update, and delete notes (CRUD operations)
* 🎨 Assign custom Hex colors to notes
* 🔍 View all notes in a clean and organized layout
* 📌 Edit existing notes with real-time updates
* 🗑️ Delete notes with ease
* 📱 Modern and responsive UI built with Jetpack Compose

🛠️ Tech Stack

* Language: Kotlin
* UI: Jetpack Compose (Material 3)
* Architecture: MVVM
* Database: Firebase Cloud Firestore
* State Management: ViewModel & Compose State
* Android Libraries: AndroidX Core KTX, Lifecycle, Activity Compose
* Build Management: Compose BOM, Firebase BOM
* Version Control: Git & GitHub

🏗️ Architecture

The application follows the MVVM (Model–View–ViewModel) architecture to maintain a clear separation of concerns. ViewModel manages the UI state and business logic, while Firebase Cloud Firestore serves as the data layer for storing and synchronizing notes, resulting in a scalable and maintainable application.

💡 Challenges & Learnings

* Implemented AndroidX Core KTX, Lifecycle, and Kotlin Coroutines to build a responsive, lifecycle-aware, and efficient application.
* Redesigned the UI to closely resemble a real notepad while creating a clean, modern, and intuitive user experience with Jetpack Compose.
* Structured the application using MVVM and integrated Firebase Cloud Firestore to deliver maintainable code and efficient CRUD operations.

📸 Screenshots/Demo

<img width="640" height="1138" alt="Notepad" src="https://github.com/user-attachments/assets/e779b764-20bd-431f-a59d-8d6d2197f6e8" />

⸻

Offline BankApp

📱 Overview

A modern offline banking application that helps users create and manage bank accounts while tracking debit and credit transactions. It also supports data reset and JSON export, providing a simple and efficient way to manage financial records locally.

✨ Key Features

* 🏦 Create and manage multiple bank accounts
* 💸 Record debit and credit transactions
* 📝 Store transaction details with account history
* 📊 View organized transaction records
* 📴 Fully offline functionality with local data storage
* 🔄 Reset all application data when required
* 📄 Export transaction data in JSON format
* 📱 Clean and intuitive Jetpack Compose UI

🛠️ Tech Stack

* Language: Kotlin
* UI: Jetpack Compose (Material 3)
* Architecture: MVVM
* State Management: ViewModel & Compose State
* Serialization: Kotlinx Serialization (JSON)
* Android Libraries: AndroidX Core KTX, Lifecycle, Activity Compose, Foundation
* Build Management: Compose BOM
* Version Control: Git & GitHub

🏗️ Architecture

The application follows the MVVM (Model–View–ViewModel) architecture to separate the UI, business logic, and data layers. ViewModel manages the application state, while the local data layer handles offline storage and JSON serialization, resulting in a scalable, maintainable, and responsive application.

💡 Challenges & Learnings

* Implemented Kotlin Serialization to export and manage transaction data efficiently in JSON format.
* Applied the Repository Pattern to separate data handling from business logic, improving code maintainability and scalability.
* Implemented a custom ViewModel Factory for proper ViewModel initialization and lifecycle-aware state management.

📸 Screenshots/Demo

<img width="640" height="1138" alt="BankinApp" src="https://github.com/user-attachments/assets/1ba84165-0242-4c8f-9205-8e8c880a95cf" />

⸻

📱 Flutter Projects

<img width="100" height="100" alt="Flutter" src="https://github.com/user-attachments/assets/8c7a6c66-4761-49e6-8f8b-e13899a02f1d" />

MealMenuApp

📱 Overview

A Flutter meal discovery app that displays meals with images and allows users to filter meals based on categories and preferences. Built with Flutter Riverpod for efficient state management and a clean, organized application architecture.

✨ Key Features

* 🍽️ Categorized Meals — Browse meals organized into different categories.
* 🔍 Meal Filtering — Filter meals based on dietary preferences and requirements.
* 📸 Meal Images — View meals with images and detailed information.
* ❤️ Favorites — Mark meals as favorites for quick access.
* 📋 Meal Details — View ingredients, preparation steps, and other meal information.
* 🧭 Category Navigation — Easily navigate between meal categories.
* ⚡ Riverpod State Management — Efficiently manage favorites and filter states.

🛠️ Tech Stack

* Framework: Flutter
* Language: Dart
* State Management: Flutter Riverpod
* UI: Flutter Widgets
* Navigation: Flutter Navigation
* Architecture: Provider-based architecture
* Assets: Images and visual resources
* Version Control: Git & GitHub

🏗️ Architecture

The application follows a feature-based architecture with Flutter Riverpod for state management. Meal data and application logic are separated from the UI, while Riverpod providers manage meal filtering, categories, and favorites, making the app modular and maintainable.

💡 Challenges & Learnings

* Learned and implemented Flutter Riverpod for efficient state management and handling application state.
* Configured Flutter asset files and integrated them with the application’s resource management.
* Implemented JSON-based data handling, ensuring meal data is correctly parsed, passed, and displayed in the UI.
* Implemented an image fallback mechanism that uses local asset images when an online image URL is unavailable or deleted.

📸 Screenshots/Demo

<img width="640" height="1491" alt="Screen_recording_20260819_134419" src="https://github.com/user-attachments/assets/e4aada56-c266-49d1-a3ca-056c4e9d8cd0" />

⸻

SpamDetector_PlatformChannelApp

📱 Overview

A Flutter-based spam message detection app that uses Flutter Platform Channels to communicate with native Kotlin code. It implements a lightweight Naive Bayes-like spam classifier based on keyword frequency to analyze messages and identify potential spam.

📸 Screenshots/Demo

<img width="640" height="1491" alt="Spam Detector" src="https://github.com/user-attachments/assets/78ca5076-4761-49d1-a3ca-056c4e9d8cd0" />

⸻

Sarcasm_Detector_NB_Classifier_App

📱 Overview

A Flutter-based sarcasm detection app that uses a JSON dataset and a Naive Bayes classifier to analyze text and determine whether a statement is sarcastic. The app demonstrates lightweight text classification and machine-learning concepts implemented directly in Flutter.

📸 Screenshots/Demo

<img width="640" height="1491" alt="Sarcasm Detector" src="https://github.com/user-attachments/assets/de60cf17-59e1-47c6-ab13-333496694ff3" />

⸻

Local_MarketPlace_App

📱 Overview

A Flutter-based local marketplace application that connects users to discover and list products within their local community. The app includes user authentication, product management, profiles, and in-app chat to support communication between buyers and sellers.

📸 Screenshots/Demo

<img width="640" height="1422" alt="Local Marketplace" src="https://github.com/user-attachments/assets/b3b8bffb-961a-45b6-8b8f-a57f46ee477e" />

⸻

⚛️ React Native Projects

<img width="100" height="100" alt="React Native" src="https://github.com/user-attachments/assets/6d9271fb-d2ca-4e76-a2a8-2bb208551095" />

Freelance_Pm_App

📱 Overview

Freelance PM is a React Native-based project management application designed to help freelancers efficiently manage their complete workflow. It provides tools for client management, project tracking, invoicing, task tracking, profiles, and an integrated chatbot in a centralized platform.

📸 Screenshots/Demo

<img width="640" height="360" alt="Freelance PM" src="https://github.com/user-attachments/assets/4a4777e8-c888-4706-b892-ac2dc7952351" />

⸻

Local_warehouse_App

📱 Overview

Local Warehouse App is a React Native application that simulates the real-world workflow of a local warehouse, helping manage products, inventory, suppliers, customers, purchase orders, sales orders, and reports.

📸 Screenshots/Demo

<img width="640" height="360" alt="Local Warehouse" src="https://github.com/user-attachments/assets/6b562add-309d-409e-9a17-5d9ba3d05f08" />

⸻

Vibe_Checked_App

📱 Overview

VibeCheck is a micro-journaling React Native app that lets users capture their mood using emojis, colors, and three-word expressions, transforming daily check-ins into a dynamic visual Mood Mosaic.

📸 Screenshots/Demo

<img width="640" height="360" alt="VibeCheck" src="https://github.com/user-attachments/assets/35f39eff-0df7-4f8f-b892-c8434c141649" />

⸻

IMA - Insurance_Management_App

📱 Overview

The Insurance Management App is a React Native application that simplifies the real-world workflow of managing insurance operations, helping manage customers, insurance companies, agents, and policies.

📸 Screenshots/Demo

<img width="640" height="360" alt="Insurance Management App" src="https://github.com/user-attachments/assets/af7f1cb8-1091-4ce9-bd6b-b96301cfb633" />

⸻

🍎 iOS Projects

<img width="100" height="100" alt="Swift" src="https://github.com/user-attachments/assets/b385e336-103c-4f3a-9b2f-1fc075077dfb" />

ShoppingCartApp

📱 Overview

🛒 Shopping Cart App is a Swift-based iOS e-commerce application built to demonstrate real-world shopping workflows. It features product browsing, cart management, quantity selection, favorites, checkout, and order history, with Firebase powering product, cart, favorite, and order data management.

✨ Key Features

* 🛍️ Product Browsing
* 🛒 Cart Management
* ➕➖ Quantity Selection
* ❤️ Favorites
* 💳 Checkout
* 📦 Order History
* 🔥 Firebase Integration
* 📱 Native iOS UI

🛠️ Tech Stack

* 🧑‍💻 Swift
* 🎨 SwiftUI
* 🔥 Firebase Firestore & Authentication
* 🏗️ MVVM
* ⚡ Async/Await
* 🧭 NavigationStack
* 🛠️ Xcode
* 🌐 Git & GitHub

🏗️ Architecture

The app follows the MVVM (Model–View–ViewModel) architecture to maintain a clean, modular, and scalable codebase. Models define product, cart, favorite, and order data, while SwiftUI Views handle the user interface and interactions. ViewModels manage UI state and business logic, communicating with Firebase for authentication and Firestore operations.

💡 Challenges & Learnings

* 📦 Learned dependency management and package integration using Swift Package Manager.
* 🔥 Gained practical experience setting up Firebase in an iOS application.
* 🏗️ Practiced separating UI and business logic using MVVM.
* 🧩 Improved understanding of clean, modular, and maintainable code structure.
* 📚 Strengthened practical Swift and SwiftUI development skills.

📸 Screenshots/Demo

<img width="640" height="1491" alt="Shopping Cart" src="https://github.com/user-attachments/assets/fa8c2f4b-c5fc-4016-b1d1-c457f47e4d55" />

⸻

NotePadApp

📱 Overview

📝 Notepad App is a Swift-based iOS note-taking application designed to demonstrate clean CRUD functionality and practical data management. Users can create, view, edit, and delete notes while customizing each note with a Hex color for better visual organization.

✨ Key Features

* 📝 Create Notes
* 👀 View Notes
* ✏️ Update Notes
* 🗑️ Delete Notes
* 🎨 Hex Color Customization
* 🔄 Complete CRUD Operations
* 📱 Simple and intuitive UI
* 🔥 Firebase Firestore Integration

🛠️ Tech Stack

* 🧑‍💻 Swift
* 🎨 SwiftUI
* 🔥 Firebase Firestore
* 🏗️ MVVM Architecture
* ⚡ Async/Await
* 🛠️ Xcode
* 🌐 Git & GitHub

🏗️ Architecture

The app follows the MVVM (Model–View–ViewModel) architecture to maintain a clean and organized codebase. The Model manages note data such as title, content, and Hex color, while SwiftUI Views handle the user interface and interactions. ViewModels manage UI state, CRUD operations, and business logic, with Firebase Firestore handling cloud data storage and retrieval.

💡 Challenges & Learnings

* 📦 Learned dependency management and package integration using Swift Package Manager.
* 🔥 Gained practical experience storing, retrieving, updating, and deleting notes with Firebase Firestore.
* 🔄 Strengthened understanding of complete CRUD implementation.
* 🎨 Practiced separating SwiftUI interface and business logic using MVVM.
* 🧩 Improved skills in building a simple, modular, and maintainable codebase.
* 📚 Strengthened practical SwiftUI development skills.

📸 Screenshots/Demo

<img width="640" height="1491" alt="Notepad" src="https://github.com/user-attachments/assets/e62c3677-402e-4d6c-a332-c13255b9a250" />

⸻

TicketApp

📱 Overview

🎫 TicketBooking App is a mobile ticket-booking application designed to provide a simple and seamless reservation experience. Users can browse available shows or events, check real-time seat availability, select preferred seats, and complete bookings through a clean and intuitive interface.

✨ Key Features

* 🎫 Ticket Booking
* 💺 Real-Time Seat Availability
* 🪑 Seat Selection
* 📋 Booking Details
* ✅ Booking Confirmation
* 📱 User-Friendly UI
* 🔄 Dynamic Seat Updates

🛠️ Tech Stack

* 🧑‍💻 Kotlin
* 🎨 Jetpack Compose
* 🔥 Firebase Firestore
* 🏗️ MVVM Architecture
* ⚡ Kotlin Coroutines
* 🧭 Navigation Compose
* 🛠️ Android Studio
* 🌐 Git & GitHub

🏗️ Architecture

The app follows the MVVM (Model–View–ViewModel) architecture to keep the booking workflow clean, modular, and easy to maintain. The Model manages event, seat, and booking data, while Jetpack Compose Views handle the user interface and interactions. ViewModels manage UI state, seat selection, booking logic, and business operations, with Firebase Firestore handling real-time seat availability and booking data.

💡 Challenges & Learnings

* 💺 Learned to manage and synchronize dynamic seat availability during bookings.
* 🎫 Implemented a complete booking workflow from seat selection to ticket confirmation.
* 🔥 Gained practical experience managing real-time event, seat, and booking data with Firebase Firestore.
* 🏗️ Practiced separating UI, business logic, and data handling using MVVM.
* ⚡ Improved understanding of state management with Jetpack Compose.
* 📱 Strengthened skills in designing a simple and intuitive booking interface.

📸 Screenshots/Demo

<img width="640" height="1491" alt="Ticket Booking" src="https://github.com/user-attachments/assets/bcd228fd-01ce-4088-b32a-8195cac90abe" />

⸻

🚀 More Projects Coming Soon

This portfolio will continue to evolve as I build, learn, and explore new technologies across Android, iOS, Flutter, and React Native.
