# AttendSure

AttendSure is a student attendance management application developed using **Flutter** and **Firebase**. The app automates attendance tracking, notifies parents of absenteeism via WhatsApp, and provides real-time attendance analytics.

## 📌 **Features**

- Real-time tracking and reporting

- Attendance analytics

- OTP and QR based Attendance marking

- WhatsApp notifications for parents

- Customizable notification preferences for parents

- Real-time student attendance dashboard

- Tracking Attendance


## 🛠 **Tech Stack**

- **Flutter**: Frontend for mobile application
- **Firebase**: Backend for database management and authentication
- **Google Maps API**: Location tracking
- **Node.js**: For server-side logic
- **Cloud Functions**: For sending notifications



## 🚀 **Getting Started**

### Prerequisites

Make sure you have the following installed:

- Flutter SDK
- Dart
- Android Studio or Visual Studio Code
- Firebase Account

### Clone the Repository

```bash
  git clone https://github.com/your-username/attensure.git
  cd attendsure
```

### Install Dependencies

Flutter uses `pubspec.yaml` for managing dependencies, similar to `requirements.txt` in Python.

```bash
flutter pub get
```

### Configure Firebase

1. Create a Firebase project.
2. Enable Firestore, Authentication, and Cloud Functions.
3. Download and add the `google-services.json` file to the `android/app` directory.
4. Set up necessary environment variables.

### Run the App

```bash
flutter run
```

## 📂 **Project Structure**

```bash
attendsure/
├── lib/
│   ├── main.dart
│   ├── pages/
│   ├── models/
│   ├── services/
├── android/
├── ios/
├── pubspec.yaml
└── README.md
```

- `lib/` contains the app's source code.
- `pubspec.yaml` manages all Flutter dependencies.

## 🧑‍💻 **Contributing**

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

## 📧 **Contact**

For any inquiries or support, contact us at: **[support@attensure.com](mailto\:support@attensure.com)**

---

**Note:** Make sure to configure your Firebase API keys securely and follow the necessary guidelines for production deployment.

Enjoy using AttendSure! 🎉

