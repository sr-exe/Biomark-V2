# 🔐 BioMark
### Biometric Attendance & Secure Authentication Android App

BioMark is a modern Android application built to provide **secure biometric authentication** and a **cloud-based attendance management system**.  
The project demonstrates real-world Android development practices with a strong focus on **security**, **Firebase integration**, and **clean UI flow**.

---

## 📌 Overview

Traditional attendance systems suffer from proxy attendance and weak authentication.  
BioMark addresses this problem by integrating **Android Biometric Authentication** with **Firebase Authentication**, ensuring that only verified users can log in and mark attendance. All attendance data is securely stored and synchronized in real time using Firebase.

---

## ✨ Features

- 🔑 Biometric authentication (Fingerprint / Device biometrics)
- 🔐 Firebase email & password authentication
- ☁️ Cloud-based attendance storage
- 📊 Admin & student panels
- 📍 Location & camera permission handling
- 🎨 Clean and structured UI flow
- 🛡 Security-first implementation

---

## 🛠 Tech Stack

- **Language:** Java  
- **Platform:** Android  
- **Authentication:** Firebase Authentication + Android Biometric API  
- **Database:** Firebase Realtime Database / Firestore  
- **IDE:** Android Studio  
- **Build Tool:** Gradle  

---

## 📱 Application Flow

1. Intro / Welcome Screens  
2. Login / Sign-up  
3. Biometric Authentication  
4. Student / Admin Dashboard  
5. Attendance Management  

---

## 📸 Screenshots

### Welcome & Intro
![Welcome Screen](Screenshots/Welcome%20Screen.PNG)
![Intro Screen](Screenshots/Intro1.PNG)

### Authentication
![Login Page](Screenshots/Login%20page.PNG)
![Sign-up Page](Screenshots/Sign-up%20page.PNG)
![Terms and Conditions](Screenshots/Terms%20and%20conditions.PNG)
![Terms and Conditions 2](Screenshots/Terms%20and%20conditions2.PNG)

### Permissions
![Camera Permission](Screenshots/Camera%20permission.PNG)
![Location Permission](Screenshots/Location%20permission.PNG)

### Panels & Dashboard
![Student Panel](Screenshots/Student%20panel.PNG)
![Admin Page](Screenshots/Admin%20page.PNG)
![Admin Dashboard](Screenshots/Admin%20Dashboard.PNG)

### Attendance & Profile
![Attendance Options](Screenshots/Attendance%20options.PNG)
![Edit Profile](Screenshots/Edit%20profile.PNG)

### Backend
![Firebase Console](Screenshots/Firebase%20console.PNG)


## 📥 Installation

### 1️⃣ Clone the Repository

git clone https://github.com/akshatcore/Biomark.git

### 2️⃣ Open the Project

Open Android Studio

Click File → Open

Select the cloned Biomark folder

### 3️⃣ Sync Gradle

Allow Android Studio to download all required dependencies

### 4️⃣ Firebase Setup

Create a project in Firebase Console

Enable Firebase Authentication

Enable Realtime Database or Firestore

Download google-services.json

Place it inside the app/ directory

### 5️⃣ Run the App

Connect a physical Android device or start an emulator

Click ▶ Run

## 📌 Usage

Launch the application

Login or sign up using email & password

Authenticate using the biometric prompt

Access Student or Admin panel

Mark and manage attendance securely

## 🚀 Future Enhancements

Role-based access control (Admin / Student)

Attendance analytics and reporting

Encrypted offline data storage

Admin web dashboard

## ⚠️ Disclaimer

This project is intended for educational and demonstration purposes.
Additional security layers and access controls are recommended for production use.
