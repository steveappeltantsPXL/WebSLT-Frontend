# WebSLT-Frontend

WebSLT-Frontend is a real-time Sign Language Translation application built with modern web technologies. This project serves as the frontend client, capturing video input, processing gestures (using MediaPipe), and communicating with the translation backend.

## 🚀 Features

- **Real-time Hand Tracking**: Utilizes Google's MediaPipe Hands for accurate and fast hand landmark detection directly in the browser.
- **Instant Translation**: Converts sign language gestures into text/speech (backend integration).
- **Modern UI**: Built with React and TypeScript for a robust and responsive user experience.
- **Fast Development**: Powered by Vite for lightning-fast HMR and building.

## 🛠️ Tech Stack

- **Framework**: [React](https://react.dev/) + [TypeScript](https://www.typescriptlang.org/)
- **Build Tool**: [Vite](https://vitejs.dev/)
- **ML/AI**: [MediaPipe Hands](https://developers.google.com/mediapipe/solutions/vision/hand_landmarker), [TensorFlow.js](https://www.tensorflow.org/js)
- **HTTP Client**: [Axios](https://axios-http.com/)
- **Notifications**: [React Toastify](https://fkhadra.github.io/react-toastify/)

## 📦 Installation

Prerequisites: Node.js (v18+ recommended) and npm/yarn/pnpm.

1. **Clone the repository:**
   ```bash
   git clone https://github.com/steveappeltantsPXL/WebSLT-Frontend.git
   cd WebSLT-Frontend
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Start the development server:**
   ```bash
   npm run dev
   ```
   Open your browser at `http://localhost:5173`.

## 🤝 Contributing

We welcome contributions! Please see [CONTRIBUTING.md](.github/CONTRIBUTING.md) for details on how to get started, our code of conduct, and the Developer Certificate of Origin (DCO).

## 📄 License

This project is licensed under the **GNU Affero General Public License v3.0 (AGPL-3.0)**. See the [LICENSE](LICENSE) file for details.

## 📝 Issue Tracking

Found a bug? Have a feature request? Please use our [Issue Tracker](https://github.com/steveappeltantsPXL/WebSLT-Frontend/issues) using the provided templates.
