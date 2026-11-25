# MY SALOON
Folder contents: index.html, manifest.json, sw.js, logo.png (add yours), firebase.json, .firebaserc, firestore.rules, firestore.indexes.json

Deploy:
  npm i -g firebase-tools
  firebase login
  firebase deploy        # hosting + firestore rules

Admin: create user in Firebase Auth, then add Firestore doc admins/<UID>.
Enable Auth > Email/Password. Restrict the API key to your domain in Google Cloud Console.
