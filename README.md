


# Video-Conferencing

This project demonstrates the implementation of a video conferencing application using VideoSDK.live. It provides a simple interface for creating and joining video meetings, with features such as screen sharing, chat, and participant management.

## Features

- Create and join video meetings
- Toggle audio and video
- Screen sharing
- Chat functionality
- Participant list
- Recording controls
- Device selection (camera, microphone, and audio output)

## Setup

1. Clone the repository:
   ```
   git clone https://github.com/abhijit826/Video-Conference
   ```

2. Navigate to the project directory:
   ```
   cd Video-Conference
   ```

3. Open `index.html` in a web browser to run the application.

## Configuration

Before running the application, you need to set up your VideoSDK credentials:

1. Sign up for an account at [VideoSDK.live](https://videosdk.live/)
2. Obtain your API key and Auth Token
3. Create a `config.js` file in the project root with the following content:

   ```javascript
   const AUTH_URL = "YOUR_AUTH_URL";
   const API_BASE_URL = "https://api.videosdk.live";
   ```

   Replace `YOUR_AUTH_URL` with your actual authentication URL.

## Usage

1. Open the application in a web browser
2. Click "Create Meeting" to start a new meeting, or enter a meeting ID and click "Join Meeting" to join an existing one
3. Use the controls at the bottom of the screen to toggle audio/video, share your screen, view participants, or access the chat

## Dependencies

- [VideoSDK JS SDK](https://docs.videosdk.live/javascript/guide/video-and-audio-calling-api-sdk/setup)
- [Bootstrap 4.4.1](https://getbootstrap.com/docs/4.4/getting-started/introduction/)
- [jQuery 3.4.1](https://jquery.com/)

## Browser Support

This application is compatible with modern web browsers that support WebRTC, including:

- Google Chrome (recommended)
- Mozilla Firefox
- Safari
- Microsoft Edge (Chromium-based)

