# 📵 DND Scheduler (Android)

A clean and modern Android app that automatically enables and disables Do Not Disturb (DND) mode based on custom user-defined schedules.

---

## ✨ Features

- 🕒 Create multiple custom schedules
- 🔁 Repeat schedules (daily or selected days)
- 🔕 Automatically turn ON DND at start time
- 🔔 Automatically turn OFF DND at end time
- 🎛 Master toggle to enable/disable all schedules
- 💾 Offline support (no API required)

---

## 📱 Screens

- Home screen with schedule list
- Add/Edit schedule screen
- Simple and modern Material UI

---

## ⚙️ Tech Stack

- Kotlin
- MVVM Architecture
- Room Database
- AlarmManager (for reliable scheduling)
- BroadcastReceiver
- NotificationManager (DND control)

---

## 🔐 Permissions Required

- Do Not Disturb Access (`ACCESS_NOTIFICATION_POLICY`)

---

## 🚀 How It Works

1. User creates a schedule  
2. App registers alarms using AlarmManager  
3. At start time → DND ON  
4. At end time → DND OFF  

---

## ⚠️ Important Notes

- App requires manual permission to control DND  
- Works offline (no internet needed)  
- Keystore must be securely stored for future updates  

---

## 📦 Build

- Release APK / AAB generated via Android Studio  
- Signed with custom keystore  

---

## 👨‍💻 Author

Shah Emtiaj

---

## 📄 License

MIT License
