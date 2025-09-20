# Firebase Setup Instructions

## Step 1: Get Firebase Configuration

1. Go to your Firebase console: <https://console.firebase.google.com/project/dlintwyoga/settings/general>
2. Scroll down to "Your apps" section
3. Click "Add app" -> Web app (\</\>)
4. Give it a name like "Yoga Practice App"
5. Copy the config object that looks like:

```javascript
const firebaseConfig = {
  apiKey: "AIzaSy...",
  authDomain: "dlintwyoga.firebaseapp.com",
  projectId: "dlintwyoga", 
  storageBucket: "dlintwyoga.appspot.com",
  messagingSenderId: "123456789",
  appId: "1:123456789:web:abcdef123456"
};
```

## Step 2: Enable Authentication

1. Go to Authentication section: <https://console.firebase.google.com/project/dlintwyoga/authentication>
2. Click "Get started"
3. Go to "Sign-in method" tab
4. Enable "Google" provider
5. Add your domain (dlintwyoga.web.app) to authorized domains

## Step 3: Enable Firestore Database

1. Go to Firestore Database: <https://console.firebase.google.com/project/dlintwyoga/firestore>
2. Click "Create database"
3. Choose "Start in test mode" for now
4. Select a location (us-central1 is fine)

## Step 4: Update the config in your HTML file

Replace the placeholder config in yoga_multicolumn.html with your real config values.
