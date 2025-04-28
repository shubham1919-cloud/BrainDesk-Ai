# BrainDesk-Ai

BrainDesk AI

BrainDesk is an advanced full-screen desktop AI assistant built for immersive, intelligent interaction. Inspired by cinematic visuals and powered by real-time voice and text commands, BrainDesk combines aesthetics with utility—functioning as a virtual desk, a visual assistant, and a personal task manager. Designed and developed solo by Shubham.


---

Features

1. Immersive Interface

Interstellar-inspired Globe: A stunning 3D globe with glowing blue rotating rings appears at launch, reminiscent of Interstellar's black hole—designed to create a visually cinematic experience.

Ambient River Background: The chat window overlays a looped river video for a calming atmosphere that enhances user focus and clarity.


2. Multi-Modal Interaction

Live Voice Interaction: A mic button at the bottom center allows real-time conversations with the AI.

Text Input: A search bar with an accessible mic icon for typed queries, ensuring inclusivity for all user preferences.


3. Persistent AI Memory

ChatLog System: BrainDesk stores every conversation and memory in ChatLog.json, allowing contextual continuity across sessions.

Adaptive Personality: Learns and evolves with user behavior, retaining custom preferences unless history is cleared.


4. Intelligent Voice Engine

Speech-to-Text Module: Utilizes a custom voice.html powered by inbuilt JavaScript and Selenium Chrome WebDriver for lightning-fast and offline-capable voice recognition.


5. Integrated App Launcher

App Recognition Engine: On first launch, app_name.json and app_name_temp.json are auto-generated to log installed app names, locations, and API triggers for instant launching via text or voice.


6. Real-Time State Management

Status Tracking: A Status.data file reflects the AI’s current activity: Available, Listening, Answering, or Searching.

Mic Tracker: Mic.data manages the mic status, ensuring responsive listening and visual cues.


7. Internal Communication System

Background Process Handler: Database.data handles all internal messages and backend tasks before responding, including system actions like “History cleared.”

AI Response Archive: Responses.data stores all generated responses for future optimization and analysis.


8. Creative Tools

Image Generator: When prompted (e.g., "Generate an image of an apple"), Image generation.data logs the task and updates its status after image generation completes.


9. Modular and Auto-Healing

Auto-Regeneration: If key files (like voice.html, ChatLog.json) are missing or deleted, BrainDesk recreates them automatically to ensure stability.

---

Upcoming Goals

In-app payment integration for premium features

Smart glasses integration with live translation, VR navigation, and face recognition

Real-time calendar and task automation

Plugin ecosystem for third-party app extension



---

Tech Stack

Python – Backend logic, file operations, and AI behavior

JavaScript + HTML – Voice processing and UI utilities

Selenium WebDriver – Voice input automation

JSON – Persistent memory and data management

Custom UI/UX – Designed for elegance and usability

---

## BrainDesk-AI: UI/UX Screenshots and Visual Preview

### Loading Screen
*Appears on app startup*
![image alt](https://github.com/shubham1919-cloud/BrainDesk-Ai/blob/6e1251c95f4d87666de5c697a23ea6025b4b85b0/Loading%20Screen.png)

### Setup Page 
*Appears at the beginning when new user installs the application to get started.*
![image alt](https://github.com/shubham1919-cloud/BrainDesk-Ai/blob/89cc458e9106b18c1a40c7d50a88d84845418edf/setup%20page.jpg)

### Initial Screen/Home
*Screen appears after the app starts*
![image alt](https://github.com/shubham1919-cloud/BrainDesk-Ai/blob/6e1251c95f4d87666de5c697a23ea6025b4b85b0/Initial%20screen.png)

### Chat Screen 
*With an immersive background video slideshow*
![image alt](https://github.com/shubham1919-cloud/BrainDesk-Ai/blob/6e1251c95f4d87666de5c697a23ea6025b4b85b0/Chatscreen.png)

### Account Dropdown menu 
*Shows the details of user (like Name, Email, Assistant-voice they selected etc.)*
![image alt](https://github.com/shubham1919-cloud/BrainDesk-Ai/blob/6e1251c95f4d87666de5c697a23ea6025b4b85b0/Account%20info%20dropdown.png)

### About 
*When user clicks on "About" button from the account info dropdown menu, the app version shows.*
![image alt](https://github.com/shubham1919-cloud/BrainDesk-Ai/blob/6e1251c95f4d87666de5c697a23ea6025b4b85b0/app%20version.png)

### Clear History 
*When user clicks on "Clear History" button from the account info dropdown menu, the previous conversation is cleared.*
![image alt](https://github.com/shubham1919-cloud/BrainDesk-Ai/blob/6e1251c95f4d87666de5c697a23ea6025b4b85b0/Clear%20chat%20hist.png)

### Give Feedback 
*When user clicks on "Give Feedback" button from the account info dropdown menu, the submit feedback page shows up.*
![image alt](https://github.com/shubham1919-cloud/BrainDesk-Ai/blob/6e1251c95f4d87666de5c697a23ea6025b4b85b0/Submit%20feedback.png)

### Sign Out 
*When user clicks on "Sign-Out" button from the account info dropdown menu, the sign-out confirmation message shows up and when pressed yes the data is erased and you need to login again.*
![image alt](https://github.com/shubham1919-cloud/BrainDesk-Ai/blob/6e1251c95f4d87666de5c697a23ea6025b4b85b0/signout.png)

---

Created by

Shubham Raj – Solo Developer | AI Enthusiast | Visionary
“BrainDesk is more than a virtual assistant—it's a personal reality companion.”
