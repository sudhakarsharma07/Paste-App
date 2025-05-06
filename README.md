# 📓 Notes Saver

A simple and efficient note-taking application built using **React**, **Tailwind CSS**, and **Redux Toolkit**, with local browser storage to save and manage notes.

## ✨ Features

- 📝 **Add, edit, and delete notes**: Seamlessly manage your notes.
- 💾 **Local Storage**: All notes are stored directly in your browser, ensuring quick access without the need for an internet connection or external databases.
- 📱 **Responsive Design**: Built with **Tailwind CSS** for a mobile-friendly and sleek user interface.
- ⚡ **Redux Toolkit**: Efficiently manages the global state of the notes for smooth interactions.

## 🛠️ Technologies Used

- ⚛️ **React**: For building the user interface
- 🎨 **Tailwind CSS**: For responsive and modern styling.
- 🗂️ **Redux Toolkit**: For managing the global state of the application.
- 💻 **Local Storage API**: For storing notes directly in the browser.

## 🚀 Installation and Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/notes-saver.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd notes-saver
   ```

3. **Install the dependencies**:
   ```bash
   npm install
   ```

4. **Start the development server**:
   ```bash
   npm start
   ```

5. Open your browser and go to:
   ```
   http://localhost:3000
   ```

## ⚙️ How It Works

- ✍️ **Adding Notes**: Enter your note content in the input field and click the "Add Note" button.
- ✏️ **Editing Notes**: Click on a note to edit it.
- 🗑️ **Deleting Notes**: Remove a note by clicking the "Delete" button next to it.

All notes are saved automatically in the browser's local storage and will remain there until manually cleared.

## 📂 Folder Structure

```
Paste-App-main/
├── node_modules/
├── public/
│   ├── icon.png
│   └── vite.svg
├── src/
│   ├── assets/
│   │   └── react.svg
│   ├── components/
│   │   ├── Home.jsx
│   │   ├── Navbar.jsx
│   │   ├── Paste.jsx
│   │   └── ViewPaste.jsx
│   ├── data/
│   │   └── Navbar.js
│   ├── redux/
│   │   ├── pasteSlice.js
│   │   └── store.js
│   ├── utils/
│   │   └── formatDate.js
│   ├── App.jsx
│   ├── index.css
│   └── main.jsx
├── .gitignore
├── eslint.config.js
├── index.html
├── netlify.toml
├── package-lock.json
├── package.json
├── postcss.config.js
├── tailwind.config.js
├── vite.config.js
└── README.md

```

