# 🏝️ Island Builder

[![Deployment: Vercel](https://img.shields.io/badge/deployed-Vercel-black?style=flat&logo=vercel)](https://vercel.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

> A lightweight, retro-style incremental game where you collect raw resources, unlock milestones, and teletransport between structural dimensions. 

This project is built as a static client application optimized for **Vercel Serverless** infrastructure, ensuring global low-latency delivery and zero-config deployment.

---

## 🕹️ Game Features & Mechanics

- **Resource Gathering:** Click environmental nodes (like the Island Tree) to harvest resources dynamically.
- **Progression Milestones:** Reaching **250 Wood** automatically triggers an advancement phase, unlocking both the **Teleporter** and the **Shop**.
- **Multi-Area Traversal:** Walk through the teleporter to leave the Island and enter the **Quarry** matrix to mine specialized stone items.
- **Dynamic Visual Feedback:** Clean click animations with fading floating text indicators providing immediate interact feedback.
- **Persistence Engine:** Fully integrated local storage support—save your resource progress and unlocked tiers, and resume exactly where you left off.

---

## 🛠️ Tech Stack & Infrastructure

- **Frontend:** Core HTML5, CSS3 (featuring custom `@keyframes` floating text animations and pixelated asset rendering), and Vanilla JavaScript (ES6) state management.
- **Hosting & Infrastructure:** Optimized for **Vercel Serverless**. The project leverages Vercel's edge network for static asset optimization, serverless routing, and instant branch previews.

---

## 🚀 Deployment & Vercel Setup

The project is configured to run flawlessly on Vercel's global edge network.

### Deploy Your Own
You can instantly deploy your own copy of this game to Vercel with a single click:

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fboredevelopers%2FIsland-Builder)

### Manual Vercel CLI Setup
To manage deployment manually via the terminal:

1. Install the Vercel CLI globally:
```bash
   npm i -g vercel
