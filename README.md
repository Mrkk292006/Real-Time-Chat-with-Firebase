# Real-Time Chat with Firebase
 <!-- Optional: Add a nice banner image to an assets folder -->

A modern, real-time chat application built on the Firebase platform. This project aims to create a unified communication ecosystem that eliminates the need for users to choose between powerful features and robust privacy.

---

## ✨ Project Vision

Our mission is to solve the **Digital Communication Paradox**. Users today are forced to juggle multiple apps: one for secure messaging, another for large communities, and a third for work. This project creates a single, integrated platform that provides both state-of-the-art **End-to-End Encryption** for private conversations and a rich, **feature-packed environment** for communities, all within one intuitive application.

---

## 🚀 Key Features

*   **Dynamic Chat Architecture:** Choose between two distinct chat modes:
    *   🔒 **Vault Mode:** For maximum privacy with default End-to-End Encryption.
    *   ☁️ **Arena Mode:** For feature-rich communities with cloud sync, bots, and powerful search.
*   **Living Communities:** Create simple group chats that can seamlessly evolve into fully-featured **Servers** with organized channels, roles, and permissions.
*   **Real-Time Everything:** Instant message delivery, typing indicators, read receipts, and online presence status.
*   **Rich Media Sharing:** Share images, videos, and files with support for large file sizes.
*   **Extensible Bot Platform:** An open platform for building and integrating smart bots and third-party services.
*   **Cross-Platform:** A consistent and seamless experience across Web, iOS, and Android.

---

## 🛠️ Technology Stack

This project uses a modern, serverless-first architecture to ensure scalability and rapid development.

*   **Backend:** [**Firebase**](https://firebase.google.com/)
    *   **Database:** Cloud Firestore
    *   **Authentication:** Firebase Authentication (Email, Phone, Google)
    *   **File Storage:** Cloud Storage for Firebase
    *   **Serverless Logic:** Cloud Functions for Firebase
*   **Frontend (Web):** [**Next.js**](https://nextjs.org/) (React Framework)
*   **Frontend (Mobile):** [**React Native**](https://reactnative.dev/)
*   **Language:** [**TypeScript**](https://www.typescriptlang.org/)
*   **Styling:** [**Tailwind CSS**](https://tailwindcss.com/)
*   **Testing:** [**Jest**](https://jestjs.io/) & [**React Testing Library**](https://testing-library.com/)
*   **CI/CD:** [**GitHub Actions**](https://github.com/features/actions)

---

## 📋 Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing.

### Prerequisites

*   [Node.js](https://nodejs.org/) (LTS version recommended)
*   [Git](https://git-scm.com/)
*   A Firebase project. You can create one for free at the [Firebase Console](https://console.firebase.google.com/).

### Installation & Setup

1.  **Clone the repository:**
    ```sh
    git clone https://github.com/Mrkk292006/Real-Time-Chat-with-Firebase.git
    cd Real-Time-Chat-with-Firebase
    ```

2.  **Install project dependencies:**
    ```sh
    npm install
    ```

3.  **Install Firebase CLI:**
    ```sh
    npm install -g firebase-tools
    ```

4.  **Log in to Firebase:**
    ```sh
    firebase login
    ```

5.  **Connect to your Firebase project:**
    Follow the on-screen prompts to associate this local project with your Firebase project.
    ```sh
    firebase use --add
    ```

6.  **Configure Environment Variables:**
    *   Create a `.env.local` file in the root of the project.
    *   Add your Firebase project configuration keys to this file. You can find these in your Firebase project settings under "Your apps" > "SDK setup and configuration".
    ```
    NEXT_PUBLIC_FIREBASE_API_KEY=your_api_key
    NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your_auth_domain
    NEXT_PUBLIC_FIREBASE_PROJECT_ID=your_project_id
    NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=your_storage_bucket
    NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
    NEXT_PUBLIC_FIREBASE_APP_ID=your_app_id
    ```

7.  **Run the Firebase Emulators:**
    For a complete offline development experience, we use the Firebase Local Emulator Suite.
    ```sh
    firebase emulators:start
    ```
    This will start local emulators for Auth, Firestore, and Functions.

8.  **Run the development server:**
    Open a new terminal window and run:
    ```sh
    npm run dev
    ```
    Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

---

## 🤝 How to Contribute

We welcome contributions! Please follow our development process to ensure a smooth workflow.

1.  **Create a Feature Branch:** Branch off from the `develop` branch.
    ```sh
    git checkout develop
    git pull
    git checkout -b feature/your-amazing-feature
    ```
2.  **Make Your Changes:** Implement your feature or bug fix.
3.  **Commit Your Changes:** Follow a consistent commit message format.
    ```sh
    git commit -m "feat: Implement message reactions"
    ```
4.  **Push to Your Branch:**
    ```sh
    git push origin feature/your-amazing-feature
    ```
5.  **Create a Pull Request:** Open a pull request from your feature branch to the `develop` branch. Please provide a clear description of your changes.

---

## 🧑‍💻 The Team

*   **Kasivishal.A** - Team Leader & Project Manager
*   **S.Marimuthu** - Lead Front-End Developer
*   **S.Madasamy** - Lead Back-End & Firebase Developer
*   **S.Madesh** - Lead QA & DevOps Engineer

---
