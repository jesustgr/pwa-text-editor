# PWA Text Editor

## Description
Welcome to the Browser Text Editor project! This single-page web application is a feature-rich text editor that not only runs seamlessly in your browser but also meets the criteria for a Progressive Web App (PWA). In addition to its core editing capabilities, this text editor employs multiple data persistence techniques to ensure your work is always safe and accessible, even when offline.

## Features
- Online and Offline Editing: Whether you're connected to the internet or not, you can create, edit, and save your text documents.
- Progressive Web App (PWA): This application meets the PWA criteria, allowing you to install it on your device and use it like a native app.
- Data Persistence: Your documents are securely stored using multiple techniques, ensuring data redundancy for peace of mind.
- IndexedDB Integration: The use of the lightweight idb package simplifies data storage and retrieval through IndexedDB.

## Installation
1. Clone this repository to your local machine

```git clone git@github.com:jesustgr/pwa-text-editor.git```

2. Navigate into the app's directory

```cd pwa-text-editor```

3. Install the dependencies and start application

```npm install```

```npm start```

## Usage

### Online Mode
1. Open your web browser and navigate to the application's URL.
2. Start creating or editing your text documents. All changes will be saved automatically, and you can access your documents from any device with an internet connection.

### Offline Mode
1. Ensure you have previously opened the application in an online environment to cache the necessary files.
2. Disconnect from the internet.
3. Open your browser and navigate to the application's URL. You can continue editing your documents without an internet connection.

## Data Persistence

### IndexedDB
The heart of the application's data persistence lies in IndexedDB, a browser-based database system that securely stores your documents. We've leveraged the idb package, a lightweight wrapper around the IndexedDB API, to simplify data management.

### Fallback Mechanism
In case IndexedDB is not supported by your browser or encounters any issues, we've implemented a fallback mechanism to ensure your data is never lost. The application will utilize alternative methods for data storage, such as local storage or service workers, to maintain data redundancy.

## Contact Me!

- GitHub: [jesustgr](https://github.com/jesustgr)
- Email: jesustgreyes@gmail.com