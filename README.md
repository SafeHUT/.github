# SafeHUT 🛡️

SafeHUT is a privacy-focused mobile application designed as an all-in-one platform for secure communication and private browsing. Built with anonymity at its core, SafeHUT ensures your digital footprint remains yours alone.

## 🚀 Features

*   **Secure Messaging:** Real-time communication via WebSockets in ephemeral, self-destructing chat rooms.
*   **Privacy-First Browser:** Incognito-by-default browsing with built-in tracker blocking and local bookmarking.
*   **Biometric Security:** App-level locking using FaceID or fingerprint recognition.
*   **Identity Management:** Easily refresh your public UID or completely destroy your account and all associated data with a single action.
*   *(Upcoming)* **VPN Integration:** Built-in VPN functionality for complete network privacy.

## 📸 Screenshots

| Secure Chat Rooms | Privacy Browser | Account & Security |
| :---: | :---: | :---: |
| <img src="assets/chat_preview.png" width="250" alt="Chat UI"/> | <img src="assets/browser_preview.png" width="250" alt="Browser UI"/> | <img src="assets/security_preview.png" width="250" alt="Security Settings"/> |

## 🛠️ Tech Stack

*   **Frontend:** Flutter
*   **Backend:** Node.js
*   **Database:** PostgreSQL
*   **Real-time:** WebSockets

## ⚙️ Getting Started

### Prerequisites
*   [Flutter SDK](https://docs.flutter.dev/get-started/install)
*   [Node.js](https://nodejs.org/)
*   [PostgreSQL](https://www.postgresql.org/)

### Installation

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/SafeHUT/safehut.git
    cd safehut
    ```

2.  **Backend Setup:**
    ```bash
    cd backend
    npm install
    # Set up your .env file with your PostgreSQL credentials and WebSocket config
    npm run dev
    ```

3.  **Frontend Setup:**
    ```bash
    cd frontend
    flutter pub get
    flutter run
    ```

## 🤝 Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License
This project is licensed under the MIT License.
