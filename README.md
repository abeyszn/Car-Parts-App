Car Parts Minna App

A mobile and backend platform to help users in Minna, Niger State easily find and buy original car parts.

🧩 Features

User registration and login (Firebase Auth)

Browse original car parts by category

Add parts to cart (coming soon)

Admin/vendor backend (planned)

Firebase integration (authentication)

RESTful backend (Node.js)



---

🚀 Tech Stack

Frontend (Flutter)

Flutter 3+

Firebase Auth

HTTP package for backend calls


Backend (Node.js)

Express.js

CORS and JSON handling



---

🛠 Setup Instructions

📱 Flutter App

1. Install Flutter SDK

https://flutter.dev/docs/get-started/install



2. Clone the repo



git clone <your-repo-url>
cd car_parts_app

3. Install dependencies



flutter pub get

4. Configure Firebase

Create Firebase project

Enable Email/Password Authentication

Add Android/iOS app and download google-services.json

Place it in android/app/

Run:




flutterfire configure

5. Run the App



flutter run

🌐 Backend (Node.js)

1. Navigate to server folder



cd backend

2. Install Node.js dependencies



npm install

3. Run the server



node server.js

Server runs on: http://localhost:3000/api/parts

> On Android emulator use http://10.0.2.2:3000 to connect Flutter to backend




---

🗂 Folder Structure

/lib
  /screens
    - home_screen.dart
    - login_screen

