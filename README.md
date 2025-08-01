# TryToHack - A Hacker Learning Platform 👾

An interactive, purely client-side project to learn common web security vulnerabilities in a playful way. The project has been completely redesigned with a modern dark-mode design and clean code.

**[➡️ View Live](https://hungryy2k.github.io/TryToHack/)**

## ✨ Challenges

| Challenge | Objective |
| :--- | :--- |
| 🔐 **Crack Login** | Gain access without knowing the password. |
| 👁️ **Uncover Content** | Make the blurred texts readable and overcome the initial overlay. |
| 🔑 **Decrypt Article** | Read the secret article without entering the correct password. |
| 🛒 **Manipulate Shop** | Complete an order for free. |
| 💬 **XSS-Challenge** | Execute your own code via the comment function. |
| 💎 **Premium-Status** | Unlock the exclusive premium content. |
| 🍪 **Admin-Access** | Access the protected admin dashboard. |
| 🏷️ **Secret Discount** | Discover and activate a secret discount at checkout. |
| ⚙️ **Form Manipulation** | Bypass a client-side disabled form field. |
| 👤 **IDOR** | View other user profiles by manipulating URL parameters. |


## 🚀 Changelog

* **Feature Expansion**: Added new challenges and a user progress tracking system.
    * **New Challenges**: Implemented "Form Manipulation" and "IDOR (Insecure Direct Object Reference)" challenges.
    * **Progress Tracking**: The application now saves completed challenges in `localStorage` and marks them with a ✅ on the main page.
* **Project-wide Translation**: All German text in the user interface, code alerts, and comments has been translated into English.
* **Code Modernization (`sha256.js`)**: The SHA-256 script has been completely refactored and modernized:
    * Converted from prototype-based functions to modern ES6 classes.
    * Replaced `var` with `const` and `let` for improved scope and readability.
    * Simplified the API and removed unnecessary complexity.

## 🛠️ Tech Stack

* **HTML5**
* **CSS3** (Dark Mode, Glassmorphism, Flexbox)
* **Vanilla JavaScript** (ES6+, encapsulated and with event listeners)
