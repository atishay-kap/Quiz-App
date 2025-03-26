Solution Details

Objective: Develop a React Native quiz game for Android and iOS.

Features:

Quiz List Screen: Displays available quizzes, tap to start.

Quiz Screen:
Shows one question at a time with four options.
"Check Answer" button enabled after selection.
Highlights correct (green) and incorrect (red) answers.
"Next" button moves to the next question.

Result Screen: Displays correct/incorrect answers summary.

Restricts back navigation once a quiz starts.

Tech Stack:
React Native, React Navigation, Context API/Redux, Async Storage (optional), Styled Components/Tailwind CSS.


Deployment Notes
Prerequisites:
Install Node.js (Latest LTS).
Install React Native CLI:
npm install -g react-native-cli

Install dependencies:
npm install

Set up Android Studio (for Android) and Xcode (for iOS).

(Optional) Install Expo:
npm install -g expo-cli

Build and Run:
Android: npx react-native run-android
iOS (Mac): npx react-native run-ios
Expo: expo start

Execution Guide
Run the app using expo start or npx react-native run-android/run-ios.
Select a quiz from the Quiz List Screen.
Answer questions and validate responses.
View results on the Result Screen.
