# 🧠 MindMend - Your Mental Wellness Companion

[![React Native](https://img.shields.io/badge/React%20Native-0.79.4-blue.svg)](https://reactnative.dev/)
[![Expo](https://img.shields.io/badge/Expo-53.0.12-blue.svg)](https://expo.dev/)
[![OpenAI](https://img.shields.io/badge/OpenAI-GPT--4-green.svg)](https://openai.com/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

**MindMend** is a privacy-focused mental wellness app that uses AI-powered cognitive behavioral therapy (CBT) techniques to help you reframe negative thoughts and improve your mental health.

## ✨ Features

### 🎯 **AI-Powered Thought Reframing**
- **6 Different Approaches**: Rational, Compassionate, Humorous, Motivational, Mindfulness, and Therapeutic
- **No Usage Limits**: Use as much as you need
- **Multi-language Support**: Available in 13 languages
- **Privacy-First**: All data stays on your device

### 🧘 **Guided Exercises**
- **Deep Breathing**: Calming breathing exercises
- **Ocean Visualization**: Stress-relief meditation
- **432Hz Relaxation**: Healing frequency audio
- **Audio-Guided**: Professional meditation sessions

### 📝 **Emotional Journal**
- **Mood Tracking**: Visual emotion selection
- **Daily Entries**: Track your emotional journey
- **Filter Options**: View by day, week, or all time
- **Secure Storage**: All entries stored locally

### 📜 **Complete History**
- **Thought Archive**: Review all your reframed thoughts
- **Progress Tracking**: See your mental wellness journey
- **Easy Management**: Delete individual entries or clear all

## 🚀 Getting Started

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn
- Expo CLI
- iOS Simulator or Android Emulator (optional)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/mindmend.git
   cd mindmend
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up OpenAI API Key**
   - Get your API key from [OpenAI](https://platform.openai.com/api-keys)
   - Replace the API key in `utils/generateReformulations.js`

4. **Start the development server**
   ```bash
   npm start
   ```

5. **Run on your device**
   - Scan the QR code with Expo Go app (iOS/Android)
   - Or press `i` for iOS simulator or `a` for Android emulator

## 📱 App Structure

```
MindMend/
├── App.js                 # Main app component with navigation
├── screens/
│   ├── HomeScreen.js      # Main input screen
│   ├── ResponsesScreen.js # AI reframing results
│   ├── HistoryScreen.js   # Thought history
│   ├── ExercisesScreen.js # Guided exercises
│   └── JournalScreen.js   # Emotional journal
├── utils/
│   ├── generateReformulations.js # OpenAI API integration
│   └── languages.js       # Multi-language support
└── assets/
    ├── images/            # App images and icons
    └── audio/             # Exercise audio files
```

## 🔧 Configuration

### OpenAI API Setup
1. Visit [OpenAI Platform](https://platform.openai.com/api-keys)
2. Create an account and get your API key
3. Replace the placeholder in `utils/generateReformulations.js`:
   ```javascript
   const API_KEY = "your-openai-api-key-here";
   ```

### Supported Languages
- English (en)
- Español (es)
- Français (fr)
- Deutsch (de)
- Português (pt)
- Italiano (it)
- Nederlands (nl)
- Polski (pl)
- 中文 (zh)
- 日本語 (ja)
- 한국어 (ko)
- हिन्दी (hi)
- العربية (ar)

## 🛡️ Privacy & Security

- **Local Storage**: All data stored on your device only
- **No Tracking**: No analytics or user tracking
- **OpenAI Privacy**: Data sent to OpenAI is not stored or used for training
- **Open Source**: Transparent code for community review

## 🏗️ Technology Stack

- **Frontend**: React Native with Expo
- **AI Integration**: OpenAI GPT-4 API
- **Storage**: AsyncStorage for local data
- **Audio**: Expo AV for guided exercises
- **Navigation**: React Navigation
- **Styling**: React Native StyleSheet

## 🤝 Contributing

We welcome contributions! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

### Development Guidelines
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## ⚠️ Medical Disclaimer

**Important**: MindMend is designed as a self-help tool and is not a substitute for professional medical or mental health treatment. If you are experiencing severe mental health issues, please seek help from qualified healthcare professionals.

## 📞 Support

- **Email**: pvyg19@yahoo.com
- **GitHub Issues**: [Report a bug](https://github.com/MORES537/mindmend/issues)
- **Privacy Policy**: [View Privacy Policy](privacy-policy.html)

## 🙏 Acknowledgments

- OpenAI for providing the GPT-4 API
- React Native and Expo communities
- All contributors and users of MindMend

---

**Made with ❤️ for mental wellness**

*Version 2.0*
