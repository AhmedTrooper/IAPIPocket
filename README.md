# APIPocket 🚀

![APIPocket Homepage](https://raw.githubusercontent.com/AhmedTrooper/APIPocket/main/readme_resources/homepage.png?token=GHSAT0AAAAAADOT5G4QQHI22RSQHN3TXJOS2K2ZHMQ)

> **A mobile-first, full-featured Postman alternative built for the modern developer.**

APIPocket redefines API development on desktop by adopting a **mobile-first design philosophy**. Built with **Tauri v2** and **React 19**, it delivers a native-like, lightweight experience that scales beautifully from small windows to full-screen workstations.

Whether you're debugging HTTP requests, streaming WebSocket messages, or organizing complex collections, APIPocket keeps your workflow smooth and efficient.

---

## ✨ Key Features

### 🔌 Advanced Protocol Support
*   **Complete HTTP Suite**: Full support for GET, POST, PUT, DELETE, PATCH, and more.
*   **WebSocket Client**: Open, manage, and debug real-time WebSocket connections with ease.
*   **OAuth 2.0 Integration**: Built-in support for Client Credentials and Auth Code flows.

### 📱 Mobile-First UX
*   **Responsive Design**: A UI that respects screen real estate, perfect for split-screen coding.
*   **Touch-Friendly**: Generous hit targets and intuitive gestures.
*   **Two-Row Navigation**: Optimized toolbar layout for smaller viewports.

### 🛠️ Powerful Tools
*   **Smart Collections**: Organize requests with folders, drag-and-drop reordering, and deep nesting.
*   **Environment Manager**: Manage global and scoped variables with `{{variable}}` substitution.
*   **Scripting Sandbox**: Run pre-request and test scripts using a JavaScript sandbox compatible with Postman syntax.
*   **Postman Compatibility**: Import your existing Postman collections (v2.1) directly.

### 💻 Developer Experience
*   **Fast & Lightweight**: Built on Rust (Tauri), consuming a fraction of the RAM of Electron apps.
*   **Code Generation**: Instant `curl` and `fetch` snippets for your requests.
*   **History Tracking**: Never lose a request with auto-saving history.

---

## 🏗️ Tech Stack

*   **Frontend**: React 19, TypeScript, Tailwind CSS v4, shadcn/ui.
*   **Backend**: Tauri v2, Rust 1.77+.
*   **State Management**: Zustand.
*   **Animation**: Motion (formerly Framer Motion).

## 🚀 Getting Started

### Prerequisites
*   Node.js 18+
*   Rust 1.77+ (for Tauri)

### Installation

```bash
# Install dependencies
npm install

# Run in development mode
npm run tauri dev
```

### Build for Production

```bash
npm run tauri build
```

---

## 🤝 Contributing

Contributions are welcome! Whether it's adding new protocol support (GraphQL, gRPC) or polishing the UI, feel free to open a PR.

## 📄 License

MIT License © 2026 Md. Ramjan Miah
