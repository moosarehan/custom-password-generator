# 🔐 Advanced Password Generator
Live Demo:https://custom-password-generator-amber.vercel.app/
A premium, highly-secure, and aesthetically pleasing Password Generator built with Vanilla Web Technologies. This tool allows users to generate cryptographically-secure-style passwords with customizable lengths and character sets, featuring a real-time strength indicator and one-click copy functionality.

## ✨ Features

- **Dynamic Length Control**: Adjust password length from 1 to 20 characters using a smooth, reactive slider.
- **Customizable Character Sets**: 
  - Toggle Uppercase (A-Z)
  - Toggle Lowercase (a-z)
  - Toggle Numbers (0-9)
  - Toggle Symbols (!@#$%^...)
- **Real-time Strength Meter**: Visual feedback (Red/Yellow/Green) based on password complexity and length.
- **Fisher-Yates Shuffle**: Implements the Fisher-Yates algorithm to ensure maximum randomness and non-predictability in character distribution.
- **One-Click Copy**: Integrated clipboard functionality with visual "Copied" feedback.
- **Premium UI/UX**: 
  - **Glassmorphism Design**: Modern translucent layers and subtle shadows.
  - **Responsive Layout**: Works seamlessly across different screen sizes.
  - **Vibrant Color Palette**: Sleek dark mode with high-contrast violet and yellow accents.

## 🛠️ Technology Stack

- **HTML5**: Semantic structure and data attributes.
- **CSS3**: 
  - Custom Properties (CSS Variables) for a consistent design system.
  - Flexbox for responsive centering.
  - Custom slider styling (`-webkit-slider-thumb`).
  - Smooth transitions and animations.
- **JavaScript (ES6+)**:
  - DOM Manipulation.
  - Async/Await for clipboard API.
  - Randomization logic using `Math.random()`.

## 🚀 Getting Started

### Prerequisites
A modern web browser (Chrome, Firefox, Edge, Safari).

### Installation
1. Clone the repository or download the files.
2. Open `index.html` in your favorite browser.

