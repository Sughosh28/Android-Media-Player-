# Media Player Android App

## Overview
The **Media Player** is a versatile Android application that allows users to browse and play music files stored on their devices. It provides an intuitive user interface with essential playback controls and additional features for an enhanced music experience.

## Features
- **Music Library:** Automatically scans and lists music files from device storage.
- **Playback Controls:** Play, pause, skip, seek, and shuffle options.
- **Song Indication:** Highlights the currently playing song in the list.
- **Shuffle & Loop Mode:** Toggle shuffle and loop functionality.
- **Mini Player:** Displays the currently playing song with basic controls.
- **Ringtone Setting:** Allows users to set a song as their ringtone.
- **Song Deletion:** Enables deleting unwanted songs directly from the app.
- **User Interface:** Designed with a visually appealing and intuitive UI.

## Technologies Used
- **Frontend:** XML (UI design for Android Studio)
- **Backend:** Java (Android development)
- **Media Playback:** `MediaPlayer` class for audio streaming
- **Storage Access:** Reading from and managing external storage
- **Broadcast Receiver:** Handles media completion and updates UI dynamically

## System Requirements
### Software Requirements
- **Operating System:** Windows/macOS/Linux
- **IDE:** Android Studio (latest version recommended)
- **Java Development Kit (JDK):** Required for Java-based development
- **Android SDK:** Must be installed with necessary dependencies

### Hardware Requirements
- **Processor:** Intel Core i5 or higher
- **RAM:** 8GB minimum
- **Storage:** At least 10-20GB of free space
- **Screen Resolution:** 1280x800 pixels or higher

## Implementation Details
### Main Components
1. **Main Activity**
   - Displays a list of songs
   - Integrates a mini player at the bottom
   - Uses `ListView` to present songs dynamically

2. **Player Activity**
   - Provides full playback controls
   - Displays the current song title and progress
   - Supports shuffle and loop options

3. **Mini Player (Custom View)**
   - Shows the currently playing song
   - Provides play and pause controls

4. **Broadcast Receiver**
   - Updates the UI dynamically when a song completes
   - Handles media transitions (next/previous track)

## Screenshots
![Splash Screen](images/splash_screen.png)
![Main Activity](images/main_activity.png)
![Mini Player](images/mini_player.png)
![Player Activity](images/player_activity.png)

## Conclusion
This project successfully implements an Android Media Player application with essential playback controls and a visually appealing UI. The app enhances the music listening experience by providing seamless song navigation, shuffle and loop functionality, and ringtone customization. 

## Contributors
- **Sughosh Athreya K N**
- **Nandan N**



