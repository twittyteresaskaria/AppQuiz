# Roshan Personality Quiz App

A fun Buzzfeed-style quiz to find out which side of Roshan matches your personality!

## Features

- 9 multiple-choice questions
- 5 possible results (Roshan personalities)
- Photo upload and name entry
- Results wall with Firebase integration
- Confetti animation on result
- Responsive design

## How to Run

Place Roshan's photo file in the workspace as `roshan.jpg`, then open `index.html` in your web browser.

## Firebase Setup (Optional)

To enable the results wall:

1. Go to [Firebase Console](https://console.firebase.google.com)
2. Create a new project
3. Enable Firestore Database (start in test mode)
4. Add a web app and copy the config
5. Replace the `FIREBASE_CONFIG` in `index.html` with your config

## Customization

Edit the `AVATARS` and `QUESTIONS` arrays in the script to change the quiz content.