# ✨ Glassmorphic Form Builder

A modern, interactive frontend workspace that allows users to dynamically build customized forms and instantly copy the generated HTML structure.

The project combines a dark cybersecurity-inspired interface with glassmorphism styling, live backdrop blur controls, dynamic form fields, validation feedback, and one-click clipboard export.

## 🌐 Live Demo

👉 **[View Live Demo](https://usamacoder14.github.io/glassmorphic-form-builder/)**

## 📸 Preview

![Glassmorphic Form Builder Preview](assets/screenshot.png)

## ✨ Features

- 🧩 **Dynamic Form Builder**
  - Add and remove form fields dynamically.
  - Supports:
    - Text inputs
    - Password inputs
    - Dropdown selection fields

- 🎨 **Live Background Blur Control**
  - Adjust the backdrop blur level using an interactive slider.
  - See styling changes in real time.

- ✅ **Interactive Validation**
  - Prevents code export when the workspace is empty.
  - Detects empty text fields before allowing code copying.
  - Displays custom error toast notifications when validation fails.

- 📋 **One-Click HTML Export**
  - Copy the generated HTML structure directly to the clipboard.
  - Displays a success toast notification after successful copying.

- 🔔 **Custom Toast Notifications**
  - Top-center feedback notifications for validation errors and successful actions.

- 📱 **Responsive Interface**
  - Built with Tailwind CSS utilities for responsive layouts and modern UI styling.

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Semantic structure and form workspace |
| Tailwind CSS | Responsive layouts, gradients, and glassmorphism styling |
| Vanilla JavaScript | Dynamic fields, validation, state management, and clipboard functionality |

## ⚙️ How It Works

1. Add the form fields you want to include in your workspace.
2. Choose from text, password, and dropdown field types.
3. Remove fields whenever necessary.
4. Adjust the background blur level using the styling control.
5. Fill in required text fields before exporting.
6. Click the copy/export action to copy the generated HTML structure.
7. The interface provides instant feedback through custom toast notifications.

## 🎯 Project Highlights

This project focuses on building an interactive frontend workspace while implementing:

- Dynamic DOM element creation
- Dynamic field management
- Client-side validation
- Real-time CSS styling controls
- Clipboard API integration
- State tracking
- Custom toast notifications
- Responsive Tailwind CSS layouts
- Glassmorphism UI design

## 📂 Project Structure

```text
glassmorphic-form-builder/
│
├── index.html
├── assets/
│   └── screenshot.png
│
└── README.md
