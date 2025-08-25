🔊 Vocalify AI - Text to Speech Converter
A modern, responsive web application that converts text to speech using AI-powered voice synthesis. Built with React and styled with Tailwind CSS, featuring a beautiful gradient interface and real-time audio controls.
Show Image
✨ Features

🎯 Real-time Text-to-Speech Conversion - Convert up to 3000 characters instantly
🎨 Modern UI/UX - Beautiful gradient design with glassmorphism effects
🔄 Live Audio Controls - Play, pause, and stop audio playback
📱 Fully Responsive - Works seamlessly on desktop, tablet, and mobile
⚡ Real-time Status - Visual indicator for AI service availability
🎛️ Character Counter - Live character count with limit visualization
🛡️ Error Handling - Comprehensive error messages and validation
🌟 Smooth Animations - Elegant hover effects and transitions

🚀 Demo
Live Demo | Video Demo
📸 Screenshots
Main Interface
Show Image
Speaking Animation
Show Image
Mobile Responsive
<img src="./screenshots/mobile-view.png" alt="Mobile View" width="300">
🛠️ Tech Stack

Frontend Framework: React 18
Styling: Tailwind CSS
Text-to-Speech: Puter AI API
Build Tool: Vite
Language: JavaScript/JSX

📋 Prerequisites

Node.js (v16 or higher)
npm or yarn package manager
Access to Puter AI platform

⚙️ Installation

Clone the repository
bashgit clone https://github.com/yourusername/vocalify-ai.git
cd vocalify-ai

Install dependencies
bashnpm install
# or
yarn install

Start the development server
bashnpm run dev
# or
yarn dev

Open your browser
Navigate to http://localhost:5173

🏗️ Project Structure
vocalify-ai/
├── public/
│   └── index.html
├── src/
│   ├── components/
│   │   └── App.jsx
│   ├── styles/
│   │   └── index.css
│   └── main.jsx
├── screenshots/
│   ├── main-interface.png
│   ├── speaking-state.png
│   └── mobile-view.png
├── package.json
├── tailwind.config.js
├── vite.config.js
└── README.md
🎮 Usage

Wait for AI Ready Status - Ensure the green "AI Ready" indicator is visible
Enter Your Text - Type or paste text (up to 3000 characters) in the textarea
Click Speak - Press the "🔊 Speak" button to convert text to speech
Control Playback - Use the "🔇 Stop" button to halt audio playback
Monitor Progress - Watch the character counter and loading animations
