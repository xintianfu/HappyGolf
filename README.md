# HappyGolf

> **Platform:** Microsoft HoloLens 2  
> **Tech:** Unity + MRTK2 · Gaze / Gesture / Voice  
> **Goal:** *Practice golf anywhere, anytime — build resilience under dynamic weather conditions.*

---

## 🧭 **Project Overview**
**HappyGolf** is an **augmented reality (AR) golf training game** designed for **HoloLens 2**.  
Using **gaze**, **gesture**, and **voice** interactions, players can practice golf *anywhere and anytime*, adapting to **rainy, snowy, and windy** environments that simulate real-world challenges.  
<u>Core value:</u> Lower the barrier to entry for golf practice, increase accessibility, and help players build stable performance across changing conditions.

<p align="center">
  <img src="docs/cover.gif" width="720" alt="HappyGolf cover demo">
</p>

🎥 **Watch on YouTube:** [https://www.youtube.com/watch?v=Qb0LGc1ehJM](https://www.youtube.com/watch?v=Qb0LGc1ehJM)

---

## 🎮 **Game Modes**
- **Practice Mode** – Learn the basic controls and environment in clear weather.  
- **Weather Mode** – Train under challenging **🌧️ rain**, **❄️ snow**, or **🌬️ wind** to build focus and adaptability.  

> ***Design insight:*** By introducing controllable environmental difficulty, the game helps players develop <ins>anticipation</ins> and <ins>emotional stability</ins> through repeated, contextualized practice.

---

## 🧠 **Core Interactions**
- **Gaze** – Target objects and place the virtual landscape using voice commands (`"Select"` → `"Place"`).  
- **Voice** – Generate the golf club and ball (`"Club"` / `"Ball"`) or reset gameplay elements.  
- **Gesture** – Grab and swing the virtual club naturally using both-hand pinch gestures.  

**Instant feedback includes:**  
**Sound effects** (club-ball impact / hole score), **scoreboard**, **ball speed**, and **coach dialogue**.

---

## 🧩 **Prototyping Process**
**Iteration highlights:**  
- Early attempts with **Vuforia / QR tracking** → shifted to **native HoloLens inputs** for stability.  
- Developed a streamlined **voice command pipeline** (`Select → Place → Club / Ball`).  
- Added a **virtual coach (Mixamo)** as guide, feedback source, and menu interface.  
- Refined synchronization between **audio and animation**, prevented scaling bugs, and stabilized **mode transitions**.  

<p align="center">
  <img src="docs/flow.png" width="740" alt="HappyGolf interaction flow">
</p>

---

## 🌦️ **Weather Simulation**
- **🌧️ Rainy Mode** – Raindrops blur the player’s view; ambient rain sound enhances immersion.  
- **❄️ Snowy Mode** – Increased ground friction reduces the ball’s rolling distance.  
- **🌬️ Windy Mode** – Wind gusts affect the ball’s trajectory and create falling leaves for visual feedback.  

> **Why weather?**  
> **Emphasis:** Training in multiple environments helps players strengthen **focus**, **control**, and **adaptive decision-making**.

---

## 🛠️ **Tech Stack**
- **Engine:** Unity + MRTK2 (Mixed Reality Toolkit)  
- **Hardware:** Microsoft HoloLens 2  
- **Audio & Animation:** 3D spatial sound, Unity Animator  
- **Assets:** Adobe Mixamo (Virtual Coach)

