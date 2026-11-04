# Medical Analysis — Mobile App 📱🩺

**Expo (React Native) app for patients to upload medical scans and test results and track their analysis.**

> 🚧 Early-stage project at [AHFID AI Labs](https://github.com/AHFIDAILabs).

➡️ Backend: [cervical_backend](https://github.com/AHFIDAILabs/cervical_backend)

## ✨ Features

- **Accounts:** sign up and log in, with tokens kept in Expo SecureStore.
- **Uploads:** add scans or results from the camera or gallery and tag the type (CT, X-ray, MRI, blood test, and more).
- **Dashboard:** track results and upload history.
- **Profile:** edit profile and manage settings.
- **Real-time updates:** delivered over Socket.IO.

## 🛠 Tech Stack

Expo · React Native · TypeScript · Expo Router / React Navigation · NativeWind (Tailwind) · Axios · Socket.IO client · Lottie · EAS Build

## 🚀 Getting Started

```bash
npm install
echo "EXPO_PUBLIC_SERVER_URL=http://<your-lan-ip>:5000" > .env
npx expo start
```

Builds run through EAS (`eas.json`).

## 👤 Author

**Fowosere Ademola Abraham** ([@Zionnaire](https://github.com/Zionnaire)), AHFID AI Labs
