# ECHO — Today, for Tomorrow

This project is based on the uploaded ECHO Mini Project Report.

## Requirements implemented
- Today screen
- Streak and total memory counters
- One memory per calendar day
- Back-camera then front-camera capture
- Front-camera image as a bordered inset
- File-input fallback if camera access fails
- Canvas JPEG resizing/compression to 720px
- Preview and Retake
- 80-character caption
- Five mood choices
- Two-minute challenge with on-time flag
- IndexedDB database `echo`, object store `days`
- Memories grid, newest first
- Memory detail dialog
- Delete with confirmation
- Demonstration notification reminder
- Service Worker cache-first offline support
- Web App Manifest and install prompt
- Responsive mobile-first layout
- No external libraries/CDNs

## Run in VS Code
1. Open this folder in VS Code.
2. Install **Live Server** by Ritwick Dey if needed.
3. Open `index.html`.
4. Right-click `index.html` → **Open with Live Server**.
5. Allow camera/notification permissions when testing those features.

## Important
Camera and Service Worker features require HTTPS or localhost. Live Server provides localhost, which is suitable for development/testing.

The report states that the reminder is a demonstration while the app is open; true scheduled daily push notifications would require a server.
