# 🟧 Mobile App

React Native + Expo mobile application for the e-commerce platform.

## 🚀 Quick Start

```bash
npm install
npx expo start
```

Scan the QR code with your phone to run the app.

## 📋 Environment Variables

Create `.env` file:

```bash
EXPO_PUBLIC_CLERK_PUBLISHABLE_KEY=<YOUR_CLERK_KEY>
SENTRY_AUTH_TOKEN=<YOUR_SENTRY_TOKEN>
EXPO_PUBLIC_STRIPE_PUBLISHABLE_KEY=<YOUR_STRIPE_KEY>
```

## 🛠️ Scripts

- `npm start` - Start Expo development server
- `npm run android` - Run on Android device/emulator
- `npm run ios` - Run on iOS device/simulator
- `npm run web` - Run in web browser

## ✨ Features

- 🛍️ Product browsing with search & filters
- 🛒 Shopping cart management
- ❤️ Wishlist functionality
- 🔐 Social authentication (Google/Apple)
- 📱 Native mobile experience
- 🗺️ Address management

## 🏗️ Tech Stack

- **Framework**: React Native + Expo
- **Navigation**: Expo Router
- **Styling**: NativeWind (Tailwind)
- **State**: TanStack Query
- **Auth**: Clerk Expo