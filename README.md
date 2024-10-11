# Simple Chat App

This is a basic chat application built using HTML, CSS, JavaScript, and Firebase Real-time Database. The app allows two users to chat in real-time by syncing their messages through Firebase.

## Features

- Real-time messaging between two users.
- Simple and clean interface.
- Messages are stored and synced using Firebase.

## How to Use

1. **Clone or Download the Repository**:
   - You can clone this repository or download the files to your local machine.

2. **Set Up Firebase**:
   - Go to [Firebase Console](https://console.firebase.google.com/) and create a new project.
   - In the "Real-time Database" section, create a new database and set the rules to public (for testing).
   - Copy the Firebase configuration details (API Key, Database URL, etc.) and replace them in the `firebaseConfig` object inside the HTML file.

3. **Host the App**:
   - You can host this app on GitHub Pages or Netlify for free.
   - Follow the instructions for hosting, and share the live URL with your friend to start chatting.

4. **Live Demo**:
   - After hosting, you and your friend can open the live link in the browser and chat in real-time.

## Technologies Used

- **HTML**: For structure and layout.
- **CSS**: For styling the app.
- **JavaScript**: For handling chat functionality and connecting to Firebase.
- **Firebase**: Real-time database to store and sync messages.

## License

This project is open-source and available under the [MIT License](LICENSE).
