# Gemini Desktop 🚀

A simple, unofficial desktop wrapper for Google Gemini, built with Electron. This app provides a native-feel experience for using Gemini on macOS, including support for passkey login with Touch ID.

![App Screenshot](https://i.imgur.com/8aZ4X7k.png)

## Features

* **Native Window**: Runs Gemini in its own dedicated window, separate from your browser tabs.
* **Passkey & Touch ID**: Supports signing in with your Google account using macOS passkeys and Touch ID.
* **Universal Build**: The application is built as a universal binary, running natively on both **Apple Silicon** (M1/M2/M3) and **Intel**-based Macs.
* **Custom Icon**: Features the Gemini logo for a clean look in your Dock and Applications folder.

***

## Prerequisites

Before you begin, ensure you have [Node.js](https://nodejs.org/) (which includes npm) installed on your system.

***

## Installation & Development

To get started with the project locally, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/gemini-app.git](https://github.com/your-username/gemini-app.git)
    cd gemini-app
    ```

2.  **Install dependencies:**
    ```bash
    npm install
    ```

3.  **Run the app in development mode:**
    ```bash
    npm start
    ```
    This will open the application window for testing.

***

## Building the Application

To build the distributable `.dmg` file for macOS:

1.  **Run the build script:**
    ```bash
    npm run build:mac
    ```

2.  **Find the installer:**
    Once the build is complete, you'll find the installer at `dist/Gemini-1.0.1.dmg`. You can share this file with others or use it to install the application on your own machine.

***

## Tech Stack

* [**Electron**](https://www.electronjs.org/)
* [**Electron Builder**](https://www.electron.build/)
