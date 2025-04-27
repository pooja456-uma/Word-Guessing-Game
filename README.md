# Word-Guessing-Game
🎯 MAD Word Guessing Game - Mobile Application
A mobile application developed for the ITE 2152 - Introduction to Mobile Application Development course.
The app challenges users to guess secret words fetched dynamically from online APIs, with a real-time scoring system, hints, and a global leaderboard.

✨ Features
🧑‍💻 Onboarding: User name input and storage using SharedPreferences.
🕹️ Guess the Word: Random word fetching from an online API, with 10 attempts and a starting score of 100 points.
📉 Dynamic Scoring:
    -10 points for wrong guesses.
    -5 points for letter checking or asking for word length.
🔤 Letter Occurrence Checking: Check how many times a letter appears in the secret word (with a point penalty).
🔍 Word Length Hint: Request the number of letters in the word.
💡 Tips: After 5 wrong guesses, users can request a rhyming word or similar word as a hint.
⏱️ Timer: Records how long it takes to guess the word correctly.
🏆 Global Leaderboard: API-connected leaderboard to track top players’ scores and times.
🎨 Intuitive UI/UX: Clean, responsive, and beginner-friendly interface.
♻️ Level Progression: Guess correctly to move to more difficult levels with longer words.

🛠 Technologies Used
Android Studio
Java
XML for UI Layouts
REST API Integration (Word APIs)
SharedPreferences for local data storage
Firebase / Mock API (for Leaderboard)
Material Design Components

📂 Project Structure
mad-word-guessing-game/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/
│   │   │   │   ├── com/yourpackage/
│   │   │   │   │   ├── activities/
│   │   │   │   │   ├── adapters/
│   │   │   │   │   ├── models/
│   │   │   │   │   ├── network/
│   │   │   │   │   ├── utils/
│   │   │   │   │   └── storage/
│   │   │   ├── res/
│   │   │   │   ├── layout/
│   │   │   │   ├── drawable/
│   │   │   │   ├── values/
│   │   │   │   └── mipmap/
│   │   │   ├── AndroidManifest.xml
├── README.md
└── Demo_Video.mp4

🚀 How to Run the Project
Clone the repository:
git clone https://github.com/yourusername/mad-word-guessing-game.git

Open the project in Android Studio.
Connect an emulator or physical Android device.
Configure API URLs (if required) inside the network module.
Run the project.

🖼 Demo
A full demo video showcasing all functionalities (onboarding, gameplay, hints, timer, leaderboard, error handling, and UI walkthrough) is included in the repository.

📚 Submission Details
Course: ITE 2152 – Introduction to Mobile Application Development
University: University of Moratuwa
Deadline: April 2025

📄 License
This project is developed for educational purposes under the BIT program at the University of Moratuwa.
Use of this project code outside educational purposes requires permission.

📣 Special Notes
Tested across different Android devices and screen sizes.
Thoroughly debugged for crashes, API failures, and bad inputs.
Focused on performance, responsiveness, and user-friendliness.


