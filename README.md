# Pomodoro
<div align="center">

# ⏳ Minimalist Pomodoro | Lo-Fi Study Edition

**A beautifully crafted productivity timer featuring an immersive anime aesthetic, seamless parallax scrolling, and a highly secure PostgreSQL backend.**

[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org/)
[![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org/)
[![Express.js](https://img.shields.io/badge/Express.js-404D59?style=for-the-badge)](https://expressjs.com/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)](https://www.postgresql.org/)

[View Live Demo](#) • [Report Bug](#) • [Request Feature](#)

</div>

<br />

## 🌌 The Vision

Most productivity apps are visually sterile. This project solves that by merging strict time management with a calming, immersive environment. It features a "Night City" aesthetic that dynamically crossfades into a "Sunrise" scene based on your focus state, complete with ambient rain audio and a sleek glassmorphism UI.

Beyond the frontend, it features a robust backend with strict user authentication rules and database constraints for saving your session history.

## ✨ Core Features

### 🎨 Immersive Frontend
* **Dynamic Aesthetics:** High-quality anime backgrounds that smoothly transition between Night and Sunrise modes globally based on user settings.
* **Parallax Scrolling:** A fixed parallax effect on the background images creates a high-end, atmospheric feel as you scroll through your session history.
* **Glassmorphism UI:** Frosted glass containers ensure high text readability without covering up the background art.
* **Animated Timer Visuals:** The 25:00 countdown features a circular pulsing border with a smooth rotating animation.
* **Ambient Audio Controls:** Integrated rain sound effects with a custom toggle for deep focus.

### 🔐 Secure Backend & Logic
* **Strict Authentication:** Custom JWT-based sign-up and login endpoints (`/api/auth/register`, `/api/auth/login`).
* **Data Validation:** Enforces strict password rules requiring exactly 8 characters with zero spaces allowed. Passwords are hashed securely using `bcryptjs`.
* **Session Tracking:** PostgreSQL database integration to store completed Pomodoro sessions and track user history.
* **Persistent Settings:** Dedicated routes to save user preferences for themes and audio toggles.

## 🛠️ Tech Stack

* **Frontend:** React.js, Tailwind CSS
* **Backend:** Node.js, Express.js
* **Database:** PostgreSQL
* **Security:** JWT (JSON Web Tokens), bcryptjs

## 📸 Visuals

*(Drag and drop your project screenshots or a short GIF of the parallax scroll here)*

## 🚀 Getting Started

To get a local copy up and running, follow these steps.

### Prerequisites
Make sure you have Node.js and PostgreSQL installed on your machine.

### Installation

1. Clone the repository:
   ```bash
   git clone [https://github.com/janvijain996/time-manager.git](https://github.com/janvijain996/time-manager.git)
