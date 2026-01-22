
# TeleChat - Beginner's Guide

## 👋 Welcome!
**TeleChat** is a modern messaging and video calling app (similar to WhatsApp or Telegram). It allows you to:
- Chat with friends in real-time.
- Make crystal-clear video calls.
- Create group chats.
- Enjoy a beautiful, easy-to-use interface.

This guide will help you run this project on your computer, even if you have never written code before!

---

## 🛠️ Prerequisites (What you need first)
Before starting, you need to download three free tools. Click the links to download and install them:

1.  **[Node.js](https://nodejs.org/)** (Required)
    *   Download the "LTS" (Long Term Support) version.
    *   Install it like any normal program.
2.  **[Git](https://git-scm.com/downloads)** (Required)
    *   Download the version for Windows.
    *   During installation, you can just click "Next" through all the options.
3.  **[VS Code](https://code.visualstudio.com/)** (Recommended)
    *   This is a friendly tool for viewing and running the project code.

---

## 🚀 How to Run the App (Step-by-Step)

### Step 1: Open the Project
1.  Open **VS Code**.
2.  Go to **File** > **Open Folder...**
3.  Select the folder where you saved this project:
    `.../teley-v2` (the folder containing this README file).

### Step 2: Open the Terminal
The terminal is where we give commands to the computer.
1.  In VS Code, look at the top menu.
2.  Click **Terminal** > **New Terminal**.
3.  A panel will open at the bottom of the screen.

### Step 3: Install Dependencies
Type the following command in the terminal and press **Enter**:
```bash
npm install
```
*Wait a minute or two while it downloads the necessary files. You might see some text scrolling by – that’s normal!*

### Step 4: Configure the App (Important!)
 This app needs some "secret keys" to connect to its database and login services.
1.  On the left side of VS Code, connect to the file explorer.
2.  Right-click in the empty space and select **New File**.
3.  Name the file: `.env.local` (don't forget the dot at the beginning!).
4.  Open this new file and paste the following configuration (You will need to ask the project owner for the actual values or set up your own Clerk/Convex/Stream accounts):

```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=replace_with_your_key
CLERK_SECRET_KEY=replace_with_your_key
CONVEX_DEPLOYMENT=replace_with_your_key
NEXT_PUBLIC_CONVEX_URL=replace_with_your_key
CLERK_JWT_ISSUER_DOMAIN=replace_with_your_key
NEXT_PUBLIC_STREAM_API_KEY=replace_with_your_key
STREAM_API_SECRET_KEY=replace_with_your_key
```

### Step 5: Start the App
Now for the magic moment! Type this command in the terminal and press **Enter**:
```bash
npm run dev
```

### Step 6: Use the App
1.  Look at the terminal output. You should see something like: `Ready on http://localhost:5000`.
2.  Open your web browser (Chrome, Edge, etc.).
3.  Type `http://localhost:5000` in the address bar and press Enter.
4.  🎉 You should see the TeleChat home page!

---

## ❓ Common Issues

**"It says `npm` is not recognized"**
*   This usually means Node.js wasn't installed correctly or you need to restart your computer after installing it.

**"Address already in use :::5000"**
*   This means the app is already running in another window. Close any other terminals and try again.

**"I see login errors"**
*   Make sure you filled out the `.env.local` file correctly with valid keys.

*   ## 📞 Contact & Support
- **Author**: Prem759‑0
- **GitHub**: https://github.com/Prem759-0
- For questions, open an issue in the repository or reach out via the GitHub Discussions page.
# Open an issue on the GitHub repository for any questions.
-Email - a70064182@gmail.com
-My WhatsApp Phone no - 9619111051

---
*Created with ❤️ by Prem Gaikwad*


