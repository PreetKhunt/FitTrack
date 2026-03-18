# 🏃‍♂️ FitTrack - Beginner Fitness App

A simple, clean fitness tracking app built with Flutter for beginners.

## ✨ Features

- **Step Counter**: Real-time step tracking using phone sensors
- **Calorie Calculator**: Automatic calculation (steps × 0.04)
- **Distance Tracker**: Shows distance in kilometers (steps × 0.0008)
- **Clean UI**: Material Design with cards and icons
- **Real-time Updates**: Live data as you walk

## 🚀 How to Run

### Prerequisites
- Flutter SDK installed
- Android device or emulator
- VS Code with Flutter extension

### Steps
1. **Clone/Download** this project
2. **Open terminal** in project folder
3. **Install dependencies:**
   ```bash
   flutter pub get
   ```
4. **Connect Android device** (enable USB debugging)
5. **Run the app:**
   ```bash
   flutter run
   ```

## 📱 How It Works

### 1. **Permission Request**
- App asks for "Physical Activity" permission
- Required to access step counter sensor

### 2. **Step Counting**
- Uses phone's built-in pedometer sensor
- Updates in real-time as you walk
- Calculates calories and distance automatically

### 3. **UI Components**
- **Header**: Shows "Today's Activity"
- **Cards**: Display steps, calories, distance
- **Icons**: Visual indicators for each metric
- **Motivation**: Encouraging message at bottom

## 🔧 Code Structure

```
lib/
├── main.dart          # Main app entry point
└── (single file app)

android/
└── app/src/main/
    └── AndroidManifest.xml  # Permissions
```

## 📚 For Beginners

### Key Concepts Learned:
- **StatefulWidget**: For dynamic data updates
- **StreamSubscription**: Listening to sensor data
- **Permission Handling**: Requesting device permissions
- **Material Design**: Cards, colors, shadows
- **State Management**: Using setState()

### Important Methods:
- `initState()`: Runs when screen loads
- `dispose()`: Cleanup when screen closes
- `setState()`: Updates UI with new data
- `build()`: Creates the visual interface

## 🎯 Formulas Used

- **Calories**: `steps × 0.04`
- **Distance**: `steps × 0.0008 km`

## 🔒 Permissions

- **ACTIVITY_RECOGNITION**: Required for step counting on Android

## 🎨 Design

- **Colors**: Blue theme with green/orange/blue accents
- **Layout**: Single column with cards
- **Typography**: Clear, readable fonts
- **Spacing**: Consistent padding and margins

## 🚀 Next Steps

To enhance this app, you could add:
- Daily step goals
- Weekly/monthly charts
- Data persistence
- Dark mode
- Multiple fitness metrics

---

Made by Preet
