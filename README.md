# Ivan Jethro Dungog | Portfolio

> AI Systems Engineer | Technical Problem Solver | RAG Architect

Welcome to the source code for my personal portfolio. Built with a focus on modern web aesthetics, glassmorphism, and interactive AI integration, this platform serves as a landing page for my professional engineering work.

## 🚀 Features

- **"Modern AI" Aesthetic Palette**: Features an OLED-Black and Midnight Violet background, with luminous Teal and Amethyst accents, echoing leading AI enterprise interfaces.
- **Interactive Cursor Spotlight**: A custom `radial-gradient` effect that follows the user's mouse, creating a highly dynamic and engaging spatial experience.
- **Glassmorphism UI Elements**: Soft frosted glass (`backdrop-filter`) creates depth for project cards and the navigation layer.
- **Embedded AI Capabilities via Worker**: Includes a custom AI chat interface hooked up to an edge Cloudflare Worker (`https://jetai.jethrodungog12.workers.dev`).
- **Markdown Support**: Chatbot safely handles and renders GenAI Markdown, styled optimally with `@tailwindcss/typography`.
- **Responsive Layout**: Designed to look beautiful entirely out of the box on mobile, tablet, and widescreen viewports using utility-first CSS.

## 🛠️ Stack

- **HTML5 & Vanilla JavaScript** (Zero heavy framework overhead)
- **Tailwind CSS** (via CDN with Typography plugin)
- **Marked.js** (For parsing Markdown from the AI API safely and beautifully)
- **FontAwesome** (For light vectorized UI iconography)

## 🔒 Security Practices Built-in

* **XSS Prevention**: The chatbot explicitly uses `textContent` when binding unverified standard user input to DOM elements, preventing script injection. HTML parsing (`innerHTML`) is strictly limited to verified Markdown coming securely back from the sanitized AI endpoint.

## 📥 Quick Start (Local dev)

Because this repository uses plain `index.html` without build steps, there is no installation required. 
1. Git clone this repository.
2. Open `index.html` in your modern browser of choice, or run via a minimal web server extension like *Live Server* in VS Code.

---

*Designed and Developed by [Ivan Jethro Dungog](#)*