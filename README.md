# BuzzRoom

BuzzRoom is a modern Android chat application built with Java, offering seamless real-time messaging and image sharing capabilities. It leverages Firebase for authentication, database management, and cloud storage, ensuring a smooth and secure user experience.

## Features

- **Real-time Messaging**: Chat one-on-one or in groups with instant message delivery.
- **OTP-based Authentication**: Secure and reliable login system using Firebase Authentication.
- **Profile Customization**: Users can set up profiles with display names and profile pictures.
- **Image Sharing**: Send and receive images seamlessly within chats.
- **User Presence & Status Updates**: Update and view user availability status.
- **Group Chat Support**: Engage in conversations with multiple users in group chats.
- **Message Reactions**: React to messages with emojis for better interaction.
- **Firebase Integration**: Uses Firebase Firestore and Firebase Storage for efficient data handling.

## Tech Stack

- **Programming Language**: Java
- **Database**: Firebase Realtime Database
- **Authentication**: Firebase Authentication (OTP-based verification)
- **Storage**: Firebase Cloud Storage
- **UI Framework**: Android XML Layouts

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/shashank11yadav/BuzzRoom.git
   ```
2. Open the project in **Android Studio**.
3. Connect the project to Firebase:
   - Go to Firebase Console (https://console.firebase.google.com/)
   - Create a new project
   - Enable Firebase Authentication (Phone Authentication)
   - Set up Firebase Realtime Database and Firebase Storage
   - Download and add the `google-services.json` file to your `app` directory.
4. Build and run the project on an Android device or emulator.

## Project Structure
```
BuzzRoom/
├── app/
│   ├── src/main/java/com/shashank/chattingapp/Activities/
│   │   ├── PhoneNumberActivity.java (Handles OTP authentication)
│   │   ├── SetupProfileActivity.java (Handles user profile setup)
│   │   ├── MainActivity.java (Main chat interface)
│   ├── src/main/res/layout/ (XML UI layouts)
│   ├── src/main/res/drawable/ (Icons and images)
├── README.md (Project Documentation)
```

## Usage
1. **Sign Up/Login**: Enter your phone number and verify with OTP.
2. **Set Up Profile**: Enter your name and optionally upload a profile picture.
3. **Start Chatting**: Search for users and start individual or group conversations.
4. **Create a Group**: Add multiple users and start a group conversation.
5. **Send Images**: Share images with your contacts.
6. **Update Status**: Let others know your current status.
7. **React to Messages**: Use emoji reactions to express yourself.

## Future Enhancements

- **Voice and Video Calls**.
- **End-to-End Encryption for Chats**.
- **Dark Mode Support**.
- **Message Editing and Deletion Features**.




