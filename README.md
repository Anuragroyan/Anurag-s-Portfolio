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

<img width="100" height="100" alt="Kotlin" src="https://github.com/user-attachments/assets/79dbc14d-1218-46ae-a627-3135b4c5fa79" />


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
* Version Control: Git & GitHub  

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
* Version Control: Git & GitHub 

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
* 📊 View organised transaction records
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
* Version Control: Git & GitHub

## Architecture:
The application follows the MVVM (Model–View–ViewModel) architecture to separate the UI, business logic, and data layers. ViewModel manages the application state, while the local data layer handles offline storage and JSON serialization, resulting in a scalable, maintainable, and responsive application.

## 💡 Challenges & Learnings:
* Implemented Kotlin Serialization to export and manage transaction data efficiently in JSON format.
* Applied the Repository Pattern to separate data handling from business logic, improving code maintainability and scalability.
* Implemented a custom ViewModel Factory for proper ViewModel initialization and lifecycle-aware state management.

## 📸 Screenshots/Demo:
<img width="640" height="1138" alt="BankinApp" src="https://github.com/user-attachments/assets/1ba84165-0242-4c8f-9205-8e8c880a95cf" />

---------------------------------------------------------------------------------------------------------------------------------------

<img width="100" height="100" alt="Flutter" src="https://github.com/user-attachments/assets/8c7a6c66-4761-49e6-8f8b-e13899a02f1d" />

## MealMenuApp
- Overview:
A Flutter meal discovery app that displays meals with images and allows users to filter meals based on categories and preferences. Built with
 Flutter Riverpod for efficient state management and a clean, organised application architecture.

## Key Features:
* 🍽️ Categorised Meals — Browse meals organised into different categories.
* 🔍 Meal Filtering — Filter meals based on dietary preferences and requirements.
* 📸 Meal Images — View meals with images and detailed information.
* ❤️ Favorites — Mark meals as favorites for quick access.
* 📋 Meal Details — View ingredients, preparation steps, and other meal information.
* 🧭 Category Navigation — Easily navigate between meal categories.
* ⚡ Riverpod State Management — Efficiently manage favorites and filter states.

## Tech Stack:
* Framework: Flutter
* Language: Dart
* State Management: Flutter Riverpod
* UI: Flutter Widgets
* Navigation: Flutter Navigation
* Architecture: Provider-based architecture
* Assets: Images and visual resources used in the application
* Version Control: Git & GitHub

## Architecture:
The application follows a feature-based architecture with Flutter Riverpod for state management. Meal data and application logic are separated from 
the UI, while Riverpod providers manage meal filtering, categories, and favorites, making the app modular and maintainable.

## 💡 Challenges & Learnings:
* Learned and implemented Flutter Riverpod for efficient state management and handling application state.
* Configured Flutter asset files and integrated them with the application’s resource management.
* Implemented JSON-based data handling, ensuring meal data is correctly parsed, passed, and displayed in the UI.
* Implemented an image fallback mechanism that uses local asset images when an online image URL is unavailable or deleted.

## 📸 Screenshots/Demo: 
<img width="640" height="1422" alt="Screen_recording_20260819_134419" src="https://github.com/user-attachments/assets/e4aada56-c266-49d1-a3ca-056c4e9d8cd0" />

## SpamDetector_PlatformChannelApp
- Overview:
A Flutter-based spam message detection app that uses Flutter Platform Channels to communicate with native Kotlin code. It implements a lightweight Naive Bayes-like
spam classifier based on keyword frequency to analyze messages and identify potential spam.

## Key Features:
* 📩 Spam Message Detection — Analyze messages and classify them as spam or legitimate.
* 🧠 Keyword-Frequency Classifier — Uses a lightweight Naive Bayes-like approach based on keyword frequency.
* 🔗 Flutter–Kotlin Communication — Uses Platform Channels to connect the Flutter UI with native Kotlin logic.
* ⚡ Real-Time Analysis — Processes the entered message and provides an immediate classification result.
* 📊 Spam Probability/Score — Evaluates the message based on detected spam-related keywords.

## Tech Stack:
* Framework: Flutter
* Language: Dart
* Native Language: Kotlin
* Platform Integration: Flutter Platform Channels
* Spam Detection: Keyword-frequency-based Naïve Bayes-like classifier
* UI: Flutter Widgets
* State Management: Flutter State Management
* Version Control: Git & GitHub  

## Architecture:
The app follows a Flutter–Native hybrid architecture, where the Flutter layer handles the UI and user interaction, while Kotlin performs the native spam classification logic. Flutter Platform Channels act as the bridge between Dart and Kotlin, passing messages for analysis and returning the classification result to the Flutter UI.

## 💡 Challenges & Learnings:
* Learned how to integrate and work with TensorFlow Lite (.tflite) models within a Flutter application.
* Implemented Flutter Platform Channels to establish communication between Flutter (Dart) and native Kotlin code.
* Developed a lightweight Naive Bayes-like spam classifier using keyword frequency to analyze and classify messages.
* Improved understanding of Flutter–native integration and combining machine-learning concepts with mobile application development.

## 📸 Screenshots/Demo: 
<img width="640" height="1422" alt="Screen_recording_20260820_010138" src="https://github.com/user-attachments/assets/78ca5076-8e5c-409e-b6b8-1637b5ec494c" />

## Sarcasm_Detector_NB_Classifier_App
- Overview:
A Flutter-based sarcasm detection app that uses a JSON dataset and a Naive Bayes classifier to analyze text and determine whether a statement is sarcastic. The app demonstrates lightweight text classification and machine-learning concepts implemented directly in Flutter.

## Key Features:
* 🧠 Sarcasm Detection — Classifies user-provided text as sarcastic or non-sarcastic.
* 📊 Naive Bayes Classification — Uses a lightweight Naive Bayes algorithm for text classification.
* 📄 JSON Dataset — Loads and processes training data from a JSON-based dataset.
* 🔤 Text Analysis — Processes input text and analyzes word patterns for classification.
* ⚡ Instant Prediction — Provides a classification result directly within the Flutter app.
* 📱 Simple Flutter UI — Clean interface for entering text and viewing prediction results.

## Tech Stack:
* Framework: Flutter
* Language: Dart
* Classification Algorithm: Naive Bayes
* Dataset: JSON
* Text Processing: Keyword/word-frequency analysis
* UI: Flutter Widgets
* Version Control: Git & GitHub  

## Architecture:
The application follows a layered architecture, separating the Flutter UI, data handling, text processing, and classification logic. The JSON dataset provides the training data, while the text-processing layer prepares the input and passes it to the Naive Bayes classifier, which returns the sarcasm prediction to the Flutter UI.

## 💡 Challenges & Learnings:
* Learned how to implement a Naive Bayes classifier using a JSON dataset to detect sarcasm in user-provided sentences.
* Implemented text processing and word-frequency analysis to train and classify sentences as sarcastic or non-sarcastic.
* Integrated Flutter Platform Channels to enable communication between the Flutter (Dart) layer and native Kotlin classification logic.
* Gained practical experience in combining Flutter, Kotlin, JSON-based data processing, and machine-learning classification in a single application.

## 📸 Screenshots/Demo:
<img width="640" height="1422" alt="Screen_recording_20260820_012614" src="https://github.com/user-attachments/assets/de60cf17-59e1-47c6-ab13-333496694ff3" />

## Local_MarketPlace_App
- Overview:
A Flutter-based local marketplace application that connects users to discover and list products within their local community. The app includes user authentication, product management, profiles, and in-app chat to support communication between buyers and sellers.

## Key Features:
* 🔐 User Authentication — Secure login and registration for buyers and sellers.
* 🛍️ Product Listings — Create and publish products with relevant details.
* 🔎 Product Discovery — Browse and explore products available in the marketplace.
* ✏️ Product Management — Add, edit, and manage listed products.
* 👤 User Profiles — View and manage personal profile information.
* 💬 In-App Chat — Communicate directly between buyers and sellers.
* ☁️ Cloud Data Management — Store and manage marketplace data using Firebase.
* 📱 Responsive Flutter UI — Clean interface designed for a smooth mobile experience.

## Tech Stack
* Framework: Flutter
* Language: Dart
* State Management: Provider
* Backend: Firebase
* Authentication: Firebase Authentication
* Database: Cloud Firestore
* UI: Flutter Widgets
* Architecture: Provider-based architecture
* Navigation: Flutter Navigation
* Version Control: Git & GitHub

## Archtecture:
The application follows a Provider-based architecture, separating the UI, application state, and data models. Provider manages marketplace state and business logic, 
while Firebase Authentication and Cloud Firestore handle user authentication and marketplace data, making the application modular and maintainable.

## 💡 Challenges & Learnings:
* Developed the Local Marketplace workflow, understanding how buyers and sellers interact through product listings, profiles, and communication.
* Implemented Provider for Flutter state management and learned efficient application state handling.
* Built a rule-based chatbot to process predefined queries and provide relevant responses.
* Integrated Firebase Authentication, Cloud Firestore, and Image Picker for user authentication, marketplace data, and product images.

## 📸 Screenshots/Demo:
<img width="640" height="1422" alt="Screen_recording_20260820_020539" src="https://github.com/user-attachments/assets/b3b8bffb-961a-45b6-b8f4-a57f46ee477e" />

--------------------------------------------------------------------------------------------------------------------------------------------------------------

<img width="100" height="100" alt="structure" src="https://github.com/user-attachments/assets/6d9271fb-d2ca-4e76-a2a8-2bb208551095" />

## Freelance_Pm_App
- Overview:
Freelance PM is a React Native-based project management application designed to help freelancers efficiently manage their complete workflow. It provides tools for client management, project tracking, invoicing, task tracking, profiles, and an integrated chatbot in a centralized platform.

## Key Features:
* 🔐 Authentication — User registration and login.
* 👥 Client Management — Add, view, and manage client records.
* 📋 Project Management — Create and manage projects for different clients.
* 🧾 Invoice Management — Create and track invoices for projects and clients.
* ⏱️ Task & Time Tracking — Track tasks and monitor work progress.
* 🤖 Rule-Based Chatbot — Provides quick assistance through predefined responses.
* 👤 Profile Management — Manage freelancer profile information.
* 📊 Centralized Dashboard — Access important freelance workflow information from one place.

## Tech Stack:
* Framework: React Native
* Language: JavaScript
* Backend: Node.js & Express.js
* Database: MongoDB
* Authentication: JWT & Firebase Authentication (if both are used)
* API Communication: Axios
* Local Storage: AsyncStorage
* UI & Navigation: React Native Screens, Safe Area Context
* Animations & Gestures: React Native Reanimated & Gesture Handler
* State Management: React Native component state/hooks
* Version Control: Git & GitHub

## Architecture:
The application follows a service-based architecture, separating the React Native UI from API communication and backend logic. The screen and component layers handle the user interface, while dedicated service modules manage authentication, clients, projects, invoices, and task tracking through REST APIs connected to the Node.js/Express backend and MongoDB database.

## 💡 Challenges & Learnings:
* Faced React Native setup and compatibility challenges, initially using Expo before migrating to React Native Community CLI for greater control.
* Switched from Firebase to MongoDB due to compatibility issues and learned to integrate Node.js, Express.js, and MongoDB with React Native.
* Implemented secure authentication middleware to protect API routes and ensure users can access only their own data, preventing unauthorized access.
* Implemented image uploads using Multer instead of storing large image data directly in MongoDB.
* Built reusable custom components such as TextInput, Button, Text, Message, and MessageBubble to improve consistency and maintainability.
* Learned to design relationships and references between MongoDB collections to connect clients, projects, invoices, and tasks effectively.
* Implemented login, registration, and MongoDB data fetching, connecting frontend screens with backend APIs and database collections.
* Built dynamic dashboard metrics by fetching database-driven data such as sales, revenue, projects, and other business statistics.

## 📸 Screenshots/Demo:
<img width="640" height="360" alt="freelance_pm" src="https://github.com/user-attachments/assets/4a4777e8-c888-4706-b892-ac2dc7952351" />

## Local_warehouse_App
- Overview:
Local Warehouse App is a React Native application that simulates the real-world workflow of a local warehouse, helping manage products, inventory, suppliers, customers, purchase orders, sales orders, and reports. It provides a centralized system for tracking warehouse operations from stock
management to sales and purchasing.

## key Features:
* 📦 Product Management — Add and manage products and their details.
* 📊 Inventory Management — Track stock levels and inventory records.
* 🏷️ Category Management — Organize products into categories.
* 👥 Customer Management — Maintain customer information and records.
* 🚚 Supplier Management — Manage supplier details and relationships.
* 🛒 Purchase Orders — Create and manage purchase orders for incoming stock.
* 💰 Sales Orders — Manage sales transactions and outgoing products.
* 📈 Reports & Dashboard — View warehouse activity and business metrics.
* 👤 User & Profile Management — Manage user accounts and profile information.
* 🔐 Authentication — Login and registration functionality for secure access.

## Tech Stack:
* Framework: React Native
* Language: JavaScript
* UI: React Native Components
* Architecture: Component-based / Service-based architecture
* Navigation: React Navigation
* API & Data Layer: Dedicated service modules for authentication, products, inventory, customers, suppliers, and orders
* State Management: React Hooks
* Version Control: Git & GitHub

## Architecture:
The application follows a component-based and service-oriented architecture, separating reusable UI components, navigation, screens, and business/data services. Dedicated service modules handle authentication and warehouse operations such as products, inventory, customers, suppliers, purchase orders, and sales orders, making the application modular, maintainable, and easier to scale.

## 💡 Challenges & Learnings:
* Faced React Native setup and compatibility challenges, initially using Expo before migrating to React Native Community CLI for greater control.
* Switched from Firebase to MongoDB due to compatibility issues and learned to integrate Node.js, Express.js, and MongoDB with React Native.
* Implemented secure authentication middleware to protect API routes and ensure users can access only their own data.
* Implemented image uploads using Multer instead of storing large image data directly in MongoDB.
* Built reusable custom components such as TextInput, Button, Text, Message, and MessageBubble for consistent and maintainable UI.
* Learned to design relationships and references between MongoDB collections to connect products, suppliers, customers, orders, and inventory data.
* Implemented login, registration, and database data fetching, connecting React Native screens with backend APIs and MongoDB collections.
* Built dynamic dashboard metrics by fetching database-driven data such as sales, revenue, inventory, and business statistics.
* Learned how navigation route names and screen names work together when passing props, particularly when navigating between screens for updating and returning data.
* Implemented product creation with related data, fetching values such as supplier and category names while handling product details including name, SKU, barcode, description, sales price, and purchase price.

## 📸 Screenshots/Demo: 
<img width="640" height="360" alt="local_warehouse" src="https://github.com/user-attachments/assets/6b562add-309d-409e-9a17-5d9ba3d05f08" />

## Vibe_Checked_App:
- Overview:
VibeCheck is a micro-journaling React Native app that lets users capture their mood using emojis, colors, and three-word expressions, transforming daily check-ins into a dynamic visual Mood Mosaic.

## Key Features:
* 😊 Quick Mood Check-In — Log your current mood quickly.
* 🎨 Mood Mosaic — Display moods in a colorful visual grid.
* 😀 Emoji-Based Mood Selection — Choose an emoji representing your current vibe.
* 📝 3-Word Mood Expression — Describe your mood with a short phrase.
* ➕ Add New Mood Entries — Record multiple mood check-ins throughout the day.
* ✏️ Edit Mood Entries — Update previously recorded moods.
* 📜 Mood History — View your previous mood check-ins.
* 🗑️ Delete Mood Entries — Remove unwanted mood records.
* 📊 Real-Time Mood Statistics — Calculate mood insights using Redux selectors.
* ⚡ Redux State Management — Manage mood data efficiently with Redux.
* 💾 Local Storage Persistence — Save mood data locally on the device.
* 📱 Clean React Native UI — Simple and responsive mobile interface.

## Tech Stack:
* ⚛️ React Native — Mobile app development
* 🟨 JavaScript — Programming language
* 🔄 Redux Toolkit — State management
* 🧭 React Navigation — Screen navigation
* 💾 AsyncStorage — Local data persistence
* 📊 Redux Selectors — Real-time mood statistics
* 🎨 React Native StyleSheet — UI styling
* Version Control: Git & GitHub

## Architecture:
VibeCheck follows a component-based architecture with centralized Redux state management. Screens handle user interactions, while Redux manages mood CRUD 
operations and application state.Selectors provide real-time insights, and local storage ensures mood data persists on the device.

## 💡 Challenges & Learnings:
* Learned to manage mood CRUD operations efficiently using Redux Toolkit.
* Improved understanding of Redux selectors for calculating real-time mood statistics.
* Learned how to implement local data persistence using AsyncStorage.
* Gained experience building a dynamic grid-based Mood Mosaic UI.
* Improved understanding of React Navigation and component-based architecture.

## 📸 Screenshots/Demo: 
<img width="640" height="360" alt="Vibecgheck" src="https://github.com/user-attachments/assets/35f39eff-0df7-4f8b-b892-c8434c141649" />

## IMA - Insurance_Management_App:
- Overview:
The Insurance Management App is a React Native application that simplifies the real-world workflow of managing insurance operations, helping manage customers, insurance companies, agents, and policies. It provides a centralized system for handling insurance data, from customer management and policy creation to tracking coverage, premiums, and policy status.

## Key Features:
* 👋 Personalised User Greeting – Displays a greeting message with the logged-in user’s name.
* 👤 Customer Management – Add, view, update, and delete customer details.
* 🏢 Insurance Company Management – Manage insurance company information.
* 🧑‍💼 Agent Management – Add and manage insurance agents.
* 🛡️ Policy Management – Create, view, update, and delete insurance policies.
* 🔗 Data Relationships – Connect policies with customers, insurance companies, and optional agents.
* 💰 Premium & Coverage Tracking – Manage policy premiums and coverage amounts.
* 📅 Policy Status Tracking – Track Active, Expired, and Cancelled policies.
* 🔐 User Authentication – Secure registration and login using JWT authentication.
* ⚠️ Frontend & Backend Error Handling – Handles validation errors, API failures, server errors, and displays user-friendly error messages.
* 🔄 Complete CRUD Operations – Perform Create, Read, Update, and Delete operations across all major modules.
* 📱 User-Friendly Mobile Interface – Clean and simple React Native interface for managing insurance operations.

## Tech Stack:
📱 React Native – Mobile app development
💻 JavaScript – Programming language
⚛️ React Hooks – State and lifecycle management
🔗 Axios – API communication
💾 AsyncStorage – Local data storage
⚙️ Node.js & Express.js – Backend development
🗄️ MongoDB & Mongoose – Database and data modeling
🔐 JWT & bcryptjs – Authentication and security
🧪 Postman – API testing
🔧 Version Control: Git & GitHub

## Architecture:
The Insurance Management App follows a structured client-server architecture, connecting the React Native mobile app with a Node.js and Express.js backend through REST APIs. The backend manages authentication and insurance-related modules, while Mongoose handles data models and relationships. All application data is securely stored and managed in MongoDB.

## 💡 Challenges & Learnings:
* Managing Model Relationships: Learned how to correctly implement the one-to-many relationship between Customers and Policies, where one customer
  can have multiple policies.
* Frontend–Backend Data Consistency: Faced issues where the frontend sent a customer ID correctly, but the backend validation expected a different data structure. Learned the importance of keeping API payloads and backend models consistent.
* Handling Related Data: Learned how to fetch and manage Customers, Insurance Companies, and Agents together using Promise.all() for better performance.
* CRUD with Relationships: Implemented policy creation, updating, and deletion while handling related MongoDB ObjectIds.
* Debugging API Errors: Learned to use console.log() and inspect backend error responses to identify issues such as “One or more customers were
  not found.”
* React Native State Management: Improved understanding of managing selected customers, companies, and agents using React useState and modal-based selection.

## 📸 Screenshots/Demo: 
<img width="640" height="360" alt="IMA" src="https://github.com/user-attachments/assets/af7f1cb8-1091-4ce9-bd6b-b96301cfb633" />

--------------------------------------------------------------------------------------------------------------------------------

<img width="100" height="100" alt="swift" src="https://github.com/user-attachments/assets/b385e336-103c-4f3a-9b2f-1fc075077dfb" />

## ShoppingCartApp
- Overview: 
🛒 Shopping Cart App is a Swift-based iOS e-commerce application built to demonstrate real-world shopping workflows. It features product browsing, cart management, quantity selection,
 favorites, checkout, and order history, with Firebase powering real-time product, cart, favorite, and order data management.

## Key Features:
* 🛍️ Product Browsing – Explore and view available products.
* 🛒 Cart Management – Add, remove, and manage products in the cart.
* ➕➖ Quantity Selection – Increase or decrease product quantities.
* ❤️ Favorites – Save products for quick access later.
* 💳 Checkout – Complete the shopping and order placement flow.
* 📦 Order History – View previously placed orders.
* 🔥 Firebase Integration – Store and manage products, carts, favorites, and orders.
* 📱 Native iOS UI – Clean and intuitive interface built with Swift.

## Tech Stack:
* 🧑‍💻 Swift – Primary iOS development language.
* 🎨 SwiftUI – Modern declarative UI framework.
* 🔥 Firebase – Firestore & Authentication for cloud data and user management.
* 🏗️ MVVM – Clean separation of UI, logic, and data layers.
* ⚡ Async/Await – Efficient asynchronous operations.
* 🧭 NavigationStack – Screen navigation and app flow.
* 🛠️ Xcode – iOS development, debugging, and testing.
* 🌐 Git & GitHub – Version control and project management.

## Architecture:
The app follows the MVVM (Model–View–ViewModel) architecture to maintain a clean, modular, and scalable codebase. Models define product, cart, favorite, and order data, while SwiftUI 
Views handle the user interface and interactions. ViewModels manage UI state and business logic, communicating with Firebase for authentication and Firestore operations.

## 💡 Challenges & Learnings:
* 📦 Swift Package Manager – Learned dependency management and package integration in iOS.
* 🔥 Firebase Setup – Gained practical experience integrating Firebase into an iOS application.
* 🏗️ Clean Architecture – Practiced separating UI and business logic for better code organization.
* 🧩 Code Structure – Improved understanding of writing clean, modular, and maintainable code.
* 📚 iOS Development – Strengthened practical Swift and SwiftUI development skills.

## 📸 Screenshots/Demo: 
<img width="640" height="1391" alt="shoppingcart" src="https://github.com/user-attachments/assets/fa8c2f4b-c5fc-4016-b1d1-c457f47e4d55" />

## NotePadApp
- Overview:
📝 Notepad App is a Kotlin-based Android note-taking application designed to demonstrate clean CRUD functionality and practical data management. Users can create, view, edit, and
 delete notes while customizing each note with a Hex color for better visual organization. The app focuses on a simple, intuitive interface with a clean and maintainable architecture.

## Key Features:
* 📝 Create Notes – Add and save new notes easily.
* 👀 View Notes – Browse saved notes in an organized layout.
* ✏️ Update Notes – Edit existing note content and details.
* 🗑️ Delete Notes – Remove unwanted notes.
* 🎨 Hex Color Customization – Assign custom colors to individual notes.
* 🔄 Complete CRUD Operations – Full Create, Read, Update, and Delete functionality.
* 📱 Simple UI – Clean and intuitive interface for easy note management.
* 🔥 Firebase Integration – Store and manage notes using Firebase.

## Tech Stack:
* 🧑‍💻 Swift – Primary programming language for iOS development.
* 🎨 SwiftUI – Declarative framework for building the user interface.
* 🔥 Firebase Firestore – Cloud database for storing and managing notes.
* 🏗️ MVVM Architecture – Separates UI, business logic, and data management.
* ⚡ Async/Await – Handles asynchronous Firebase operations.
* 🛠️ Xcode – iOS development, debugging, and testing.
* 🌐 Git & GitHub – Version control and project management.

## Architecture:
The app follows the MVVM (Model–View–ViewModel) architecture to maintain a clean and organized codebase. The Model manages note data such as title, content, and Hex color, 
while SwiftUI Views handle the user interface and interactions. ViewModels manage UI state, CRUD operations, and business logic, with Firebase Firestore handling cloud data 
storage and retrieval.

## 💡 Challenges & Learnings:
* 📦 Swift Package Manager – Learned dependency management and package integration in an iOS project.
* 🔥 Firebase Firestore – Gained practical experience storing, retrieving, updating, and deleting notes.
* 🔄 CRUD Implementation – Strengthened understanding of implementing complete Create, Read, Update, and Delete operations.
* 🎨 UI & Business Logic Separation – Practiced separating SwiftUI interface from application logic using MVVM.
* 🧩 Clean Code Structure – Improved skills in building a simple, modular, and maintainable codebase.
* 📚 SwiftUI Development – Strengthened practical iOS development skills through a real-world note-taking application.

## 📸 Screenshots/Demo: 
<img width="640" height="1391" alt="notepad" src="https://github.com/user-attachments/assets/e62c3677-402e-4d6c-a332-c13255b9a250" />

## TicketApp
- Overview:
🎫 TicketBooking App is a mobile ticket-booking application designed to provide a simple and seamless reservation experience. Users can browse available shows or events, check real-time seat availability, select preferred seats, and complete bookings through a clean and intuitive interface.

## Key Features:
* 🎫 Ticket Booking – Book tickets through a simple and streamlined flow.
* 💺 Real-Time Seat Availability – View available and occupied seats instantly.
* 🪑 Seat Selection – Select preferred seats before confirming a booking.
* 📋 Booking Details – Review selected seats and booking information.
* ✅ Booking Confirmation – Complete and confirm ticket reservations.
* 📱 User-Friendly UI – Clean and intuitive interface for a smooth booking experience.
* 🔄 Dynamic Seat Updates – Keep seat availability synchronized during bookings.

## Tech Stack:
* 🧑‍💻 Kotlin – Primary programming language for Android development.
* 🎨 Jetpack Compose – Modern declarative UI toolkit.
* 🔥 Firebase Firestore – Stores and manages events, seats, and booking data.
* 🏗️ MVVM Architecture – Separates UI, business logic, and data management.
* ⚡ Kotlin Coroutines – Handles asynchronous operations efficiently.
* 🧭 Navigation Compose – Manages navigation between app screens.
* 🛠️ Android Studio – Development, debugging, and testing.
* 🌐 Git & GitHub – Version control and project management.

## Architecture:
The app follows the MVVM (Model–View–ViewModel) architecture to keep the booking workflow clean, modular, and easy to maintain. The Model manages event, seat, and booking data, while Jetpack Compose Views handle the user interface and interactions. ViewModels manage UI state, seat selection, booking logic, and business operations, with Firebase Firestore handling real-time seat availability and booking data.

## 💡 Challenges & Learnings:
* 💺 Real-Time Seat Availability – Learned to manage and synchronize dynamic seat availability during bookings.
* 🎫 Booking Workflow – Implemented a complete flow from seat selection to ticket confirmation.
* 🔥 Firebase Firestore – Gained practical experience managing real-time event, seat, and booking data.
* 🏗️ MVVM Architecture – Practiced separating UI, business logic, and data handling for cleaner code.
* ⚡ State Management – Improved understanding of managing seat selection and booking states with Jetpack Compose.
* 📱 UI Design – Strengthened skills in creating a simple and intuitive booking interface.

## 📸 Screenshots/Demo: 
<img width="640" height="1391" alt="ticket" src="https://github.com/user-attachments/assets/bcd228fd-01ce-4088-b32a-8195cac90abe" />




