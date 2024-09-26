# Next Google Docs 🚀

Welcome to **Next Google Docs**, a full-featured real-time document editing web application. This project leverages the power of **Draft.js** for a seamless text editing experience and **Firebase** for robust data storage and synchronization. Whether you are collaborating on documents or managing your personal work, this app is designed to enhance productivity through a smooth, responsive interface with real-time auto-saving.

⚡ Built with scalability and security in mind, **Next Google Docs** integrates **NextAuth.js** for secure, user-friendly authentication, ensuring that your documents are safe and accessible only to authorized users.

## ✨ Features

- **Real-time Collaboration**: Edit your documents in real-time with auto-saving, allowing you to focus on your work without worrying about manual saves.
- **Responsive Design**: Fully optimized for desktops, tablets, and mobile devices, ensuring a consistent and intuitive experience across all platforms.
- **Dark Mode Support**: Switch between light and dark themes based on your preference for a comfortable editing experience.
- **Document Management**: Effortlessly create, edit, delete, and download documents, all with a few clicks.
- **Secure Authentication**: Integrated with **NextAuth.js**, providing secure login options via Google to protect your account and documents.

## 🚀 Technologies Used

- [**Next.js**](https://nextjs.org/) for building a fast, responsive, and scalable application.
- [**Draft.js**](https://draftjs.org/) for rich text editing capabilities.
- [**Firebase**](https://firebase.google.com/) for real-time database and storage.
- [**NextAuth.js**](https://next-auth.js.org/) for seamless authentication.
- [**Material Tailwind**](https://material-tailwind.com/) and [**Tailwind CSS**](https://tailwindcss.com/) for elegant and responsive UI design.

## 🛠 How to Get Started

1. **Create a Next.js App**:
   Open your terminal and run the following command to create your Next.js project:
   ```bash
   $ npx create-next-app <project-name>
   ```

2. **Start the Development Server**:
   Navigate to your project directory and start the development server:
   ```bash
   $ cd <project-name>
   $ npm run dev
   ```

3. **Install Tailwind CSS**:
   Set up Tailwind CSS by running:
   ```bash
   $ npm install -D tailwindcss postcss autoprefixer
   $ npx tailwindcss init -p
   ```
   Follow the official [Tailwind CSS Next.js Guide](https://tailwindcss.com/docs/guides/nextjs) to configure `tailwind.config.js`.

4. **Configure Environment Variables**:
   Set up `.env.local` with the following variables:
   - `NEXTAUTH_URL`: Use `https://localhost:3000` for development or your production URL.
   - `GOOGLE_CLIENT_ID` and `GOOGLE_CLIENT_SECRET`: Obtain these from the [Google Cloud Console](https://console.cloud.google.com/) by creating an OAuth 2.0 Client.

## 🖼 App Overview

### 🔑 Login Screen
| Desktop | Tablet | Mobile |
| --- | --- | --- |
| ![Login Desktop](https://i.imgur.com/zyEQWwR.png) | ![Login Tablet](https://i.imgur.com/D1ifDG4.png) | ![Login Mobile](https://i.imgur.com/lFCNUQW.png) |

### 🏠 Home Screen After Login
| Desktop | Mobile |
| --- | --- |
| ![Home Desktop](https://i.imgur.com/762sH1K.png) | ![Home Mobile](https://i.imgur.com/RIOvsAy.png) |

### 📝 Document Screen
| Desktop | Mobile |
| --- | --- |
| ![Doc Desktop](https://i.imgur.com/1bpGTpc.png) | ![Doc Mobile](https://i.imgur.com/2KsdqlE.png) |

## ⚡ Core Functionalities

### 🌙 Dark Mode
Easily toggle between light and dark themes for a personalized editing experience.
![Dark Mode](https://i.imgur.com/Tus9rT5.gif)

### ➕ Create New Document
Effortlessly create a new document by clicking the **+** button, entering the document name, and beginning your work.
![Create Document](https://i.imgur.com/cp3f9Hg.gif)

### 🔄 Open Document in New Tab
You can open any document in a new tab directly from the document list, enhancing multitasking and productivity.
![Open in New Tab](https://i.imgur.com/8nswhFB.gif)

### 🗑️ Delete Document
To delete a document, click the three dots next to the document name, select **Delete**, and confirm. Your document will be permanently removed.
![Delete Document](https://i.imgur.com/Mcmr0SL.gif)

### ✍️ Edit Document
Modify your document as you like using rich text editing features, including font styling and formatting, available via the editor toolbar.
![Edit Document](https://i.imgur.com/MbJGuG8.gif)

### 📥 Download as PDF
Download your documents as PDFs with a single click, making it easy to share or archive your work.
![Download PDF](https://i.imgur.com/3zyMXLy.png)

### 🔒 Logout
Securely log out from the app by clicking on your profile icon in the top-right corner.
![Logout](https://i.imgur.com/mkhpPYv.png)

## 🔐 Security & Privacy Warning
⚠️ **Please Note**: This project is still under development and is **not end-to-end encrypted**. As an admin, I currently have access to view all user documents. This is intended as a learning project and will be improved in the future.

