# ToTravel 🧳✈️

*A comprehensive travel-sharing Android application built with Kotlin and Jetpack Compose for the **Mobile Application Development** course at Politecnico di Torino (PoliTo).*

---

## 📱 About  
**ToTravel** is a feature-rich travel companion app that lets users create, discover and join travel experiences. Travellers can organise trips, connect with fellow explorers and manage every aspect of their adventures in one place.

---

## ✨ Key Features

### 🗺️ Travel Management
- **Create Travel Proposals** – plan trips with detailed itineraries  
- **Browse & Discover** – explore opportunities shared by other users  
- **Join Adventures** – apply for trips that match your interests  
- **Manage Applications** – accept or reject requests for the trips you organise  

### 👥 Social Features
- **User Profiles** – personalised profiles with travel preferences  
- **Real-time Chat** – communicate with travel companions  
- **Review System** – rate trips and fellow travellers  
- **Push Notifications** – stay up to date on activities and messages  

### 🔧 Advanced Functionality
- **Interactive Maps** – Google Maps integration for locations  
- **Smart Matching** – algorithmic recommendations based on interests & destinations  
- **Photo Sharing** – capture and share memories  
- **Widget Support** – home-screen widget for upcoming travels  
- **Offline Support** – network-connectivity awareness  

---

## 🛠️ Technical Stack

### Frontend
- **Kotlin** (≈ 97 % of codebase)  
- **Jetpack Compose** – modern UI toolkit  
- **Material 3** – latest Material components  
- **Navigation Compose** – type-safe navigation  
- **CameraX** – camera functionality  
- **Coil** – image loading  

### Backend & Services
- **Firebase Ecosystem**  
  • Firebase Authentication  
  • Firestore Database  
  • Firebase Storage  
  • Firebase Cloud Messaging (FCM)  
  • Firebase Crashlytics  
  • Firebase Performance Monitoring  
- **Google Maps Platform**  
  • Maps SDK  
  • Places API  
  • Location Services  

### Architecture
- **MVVM** with ViewModels  
- **Repository Pattern** for data management  
- **Coroutines & Flow** for async programming  
- **Dependency-injection-ready** structure  

---

## 🚀 Getting Started

### Prerequisites
- **Android Studio** (latest version recommended)  
- **Android SDK** API 31 +  
- **Google Services** configuration  

### Setup
```bash
# Clone the repository
git clone https://github.com/<your-user>/ToTravel.git
cd ToTravel
```

#### Configure Firebase
1. Create a new Firebase project.  
2. Add **google-services.json** to `android_app/app/`.  
3. Enable Auth, Firestore, Storage and FCM.  

#### Configure Google Maps
1. Obtain a Google Maps API key.  
2. Create a `secrets.properties` file in the project root:
```
MAPS_API_KEY=your_api_key_here
```

#### Build and Run
```bash
cd android_app
./gradlew assembleDebug
```

---

## 📁 Project Structure
```
ToTravel/
├── android_app/                 # Main Android application
│   ├── app/src/main/java/com/example/totravel/
│   │   ├── ui/screens/          # Compose UI screens
│   │   ├── ui/widget/           # Home-screen widgets
│   │   ├── utils/               # Utility classes
│   │   └── MainApplication.kt   # Application class
│   └── build.gradle.kts         # App-level build config
└── functions/                   # Firebase Cloud Functions
    └── index.js                # Notification handling logic
```

---

## 🎯 Core Screens
- **Travel Proposal List** – browse available trips  
- **Travel Creation / Management** – create and edit proposals  
- **Travel Details** – view trip info and apply  
- **User Profile** – manage personal data and preferences  
- **Chat System** – real-time messaging  
- **Reviews** – rate experiences  
- **Notifications** – stay informed about activities  

---

## 🔐 Features Implemented

### Authentication & User Management
- Email/password sign-in  
- Profile setup & management  
- Email verification  
- Password reset  

### Travel System
- Trip creation with interactive maps  
- Itinerary planning with multiple stops  
- Application management (accept/reject participants)  
- Travel status tracking  
- Smart recommendation system  

### Communication
- Real-time chat between participants  
- Push notifications for important updates  
- In-app notification system  

### Additional Features
- Camera integration for photo capture  
- Location services & GPS integration  
- Offline connectivity handling  
- Home-screen widgets  
- Performance monitoring & crash reporting  

---

## 🎨 UI / UX Highlights
- **Material 3** design with dynamic theming  
- Responsive layouts for multiple screen sizes  
- Smooth animations and transitions  
- Dark / Light theme support  
- Accessibility considerations  

---

## 📊 Performance & Quality
- ProGuard optimisation for release builds  
- Crashlytics integration for error tracking  
- Performance monitoring with Firebase  
- Memory-efficient image loading (Coil)  
- Network state awareness  

---

## 🤝 Contributing
This project was developed as part of the **Mobile Application Development** course at Politecnico di Torino.

---

## 📄 License
This project is intended for educational purposes as part of an academic course at PoliTo.
