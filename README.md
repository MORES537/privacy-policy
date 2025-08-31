🧠 MindMend — Your Mental Wellness Companion








MindMend is a privacy-focused mental wellness app that uses AI-assisted cognitive behavioral techniques (CBT) to help reframe negative thoughts and support daily wellbeing.

✨ Features
🎯 AI-Powered Thought Reframing

6 approaches: Rational, Compassionate, Humorous, Motivational, Mindfulness, Therapeutic

No in-app usage limits

Multi-language: 13 languages

Privacy-first: history & journal stored locally

🧘 Guided Exercises

Deep Breathing • Ocean Visualization • 432Hz Relaxation

Audio-guided sessions using Expo AV

📝 Emotional Journal

Mood tracking with visual selection

Daily entries & filters (day/week/all-time)

Secure local storage

📜 Complete History

Review all reframed thoughts

Progress at a glance

Delete single items or clear all

🚀 Getting Started
Prerequisites

Node.js 18+

npm or yarn

Xcode (iOS) / Android Studio (Android) if you use simulators/emulators

Installation
git clone https://github.com/MORES537/mindmend.git
cd mindmend
npm install

OpenAI API Key

⚠️ This is a client-only app. Any API key embedded in a mobile app is not secret. For production-grade security, use your own backend proxy. If you keep it client-side, rotate the key periodically and set sensible rate limits in your OpenAI account.

Set your key in utils/generateReformulations.js:

const API_KEY = "your-openai-api-key-here";

Run
npm start            # Expo dev server
# then press 'i' for iOS simulator, 'a' for Android emulator, or scan QR with Expo Go

📱 App Structure
MindMend/
├── App.js
├── screens/
│   ├── HomeScreen.js
│   ├── ResponsesScreen.js
│   ├── HistoryScreen.js
│   ├── ExercisesScreen.js
│   └── JournalScreen.js
├── utils/
│   ├── generateReformulations.js
│   └── languages.js
└── assets/
    ├── images/
    └── audio/

🔧 Configuration
Supported Languages

English, Español, Français, Deutsch, Português, Italiano, Nederlands, Polski, 中文, 日本語, 한국어, हिन्दी, العربية.

🛡️ Privacy & Security

Local storage: your journal, history, and preferences stay on your device.

No tracking: no analytics SDKs, no ads.

AI processing: when you request an AI response, the text (and voice, if enabled) is sent to OpenAI’s API only to generate that response.

OpenAI does not use API data to train its models by default and may retain it for up to 30 days for abuse/security monitoring before deletion (unless legally required to retain it).

See the full policy: privacy-policy.html

🏗️ Technology Stack

React Native (Expo)

OpenAI API (GPT models)

AsyncStorage for local data

Expo AV for audio

React Navigation

🤝 Contributing

Contributions are welcome!

Fork → 2) git checkout -b feature/AmazingFeature → 3) Commit → 4) PR.

📄 License

MIT — see LICENSE
.

⚠️ Medical Disclaimer

MindMend is a self-help tool, not medical advice or a substitute for professional care. If you experience severe distress, seek qualified help.

📞 Support

Email: pvyg19@yahoo.com

GitHub Issues: Report a bug

Privacy Policy: View

Made with ❤️ for mental wellness — Version 2.0
