
---

# Real-Time Collaborative Code Editor

A **real-time code editor** designed for seamless collaboration, allowing users to work on projects together in real-time. With support for various programming languages, file management, and collaborative features, it's a powerful platform for both learning and professional development.

## 🔮 Features

- **💻 Real-time Collaboration**: Edit code together with multiple users across different files.
- **📁 File Management**: Create, open, edit, save, delete, and organize files and folders effortlessly.
- **💾 Download Codebase**: Download the entire project as a zip file for offline access.
- **🚀 Unique Room ID**: Collaborate instantly by sharing a unique room ID for each session.
- **🌍 Language Support**: Supports multiple programming languages, enabling flexible collaboration.
- **🌈 Syntax Highlighting**: Auto-language detection and syntax highlighting for a variety of file types.
- **🚀 Code Execution**: Run your code directly within the environment and get instant feedback.
- **⏱️ Real-time Synchronization**: Code changes are instantly updated and synchronized for all users in the session.
- **📣 Notifications**: Get notified when users join or leave the collaboration session.
- **👥 User Presence List**: View a list of users currently in the session, with online/offline status indicators.
- **💬 Real-time Chat**: Chat with collaborators while working on the code.
- **🎩 Live Tooltip**: See which users are actively editing specific parts of the code.
- **💡 Code Suggestions**: Auto-suggestions based on the programming language to help speed up coding.
- **🔠 Customization**: Adjust font size and font family to suit your preferences.
- **🎨 Theming**: Choose from multiple themes for a personalized coding experience.
- **🎨 Collaborative Drawing**: Sketch and draw with your team in real-time to visualize ideas.

## 🚀 Live Preview

Check out the live demo of the project [here](https://code-sync-live.vercel.app/).

## 💻 Tech Stack

- ![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
- ![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
- ![React Router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white)
- ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
- ![NodeJS](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
- ![ExpressJS](https://img.shields.io/badge/Express.js-404D59?style=for-the-badge)
- ![Socket.io](https://img.shields.io/badge/Socket.io-ffffff?style=for-the-badge)
- ![Git](https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white)
- ![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)
- ![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

## ⚙️ Installation

To get started with the project, follow these steps:

1. **Fork the Repository**:  
   Click the "Fork" button at the top-right corner of this page to fork the repository.

2. **Clone the Repository**:  
   ```bash
   git clone https://github.com/brittytino/Real-Time-Code-Editor.git
   ```

3. **Set up Environment Variables**:  
   Rename the `.env.example` files in the `client` and `server` directories to `.env` and set the following environment variables:

   **Frontend (`client`):**
   ```bash
   VITE_BACKEND_URL=<your_server_url>
   ```

   **Backend (`server`):**
   ```bash
   PORT=3000
   ```

4. **Install Dependencies**:  
   Navigate to the frontend and backend directories separately and install the necessary dependencies:
   ```bash
   npm install
   ```

5. **Start the Servers**:  
   - Frontend:  
     ```bash
     cd client
     npm run dev
     ```
   - Backend:  
     ```bash
     cd server
     npm run dev
     ```

6. **Access the Application**:  
   Open a browser and visit:
   ```bash
   http://localhost:5173/
   ```

## 🔮 Upcoming Features

- **Admin Permissions**: Introduce an admin permission system to manage user access levels and control over certain platform features.

## 🤝 Contribute

We welcome contributions! If you'd like to report a bug, suggest a new feature, or contribute to the project, please refer to the [contribution guidelines](CONTRIBUTING.md) to get started.

## 🌟 Support Us

If you find this project useful, please consider giving it a star ⭐ on GitHub. It helps the project gain visibility and motivates further development. Thank you for your support!

## 🧾 License

This project is licensed under the [MIT License](LICENSE).

## 🌟 Acknowledgments

Special thanks to **EMKC** for providing the **Piston API**, which enables code execution functionality in the project. For more information, check out:

- [Piston Repository](https://github.com/engineer-man/piston)
- [Piston Documentation](https://piston.readthedocs.io/en/latest/api-v2/)

---

This version is more polished, better formatted, and emphasizes the key sections in a more readable layout. Let me know if you need further adjustments!
