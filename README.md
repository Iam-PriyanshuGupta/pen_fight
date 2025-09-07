# Pen Fight Arena ⚔️  

A real-time, online multiplayer Pen Fight game built with modern web technologies. Knock your opponents off the table to be the last one standing in this physics-based classic!  

This project brings the nostalgic tabletop game to the web, complete with realistic physics, online multiplayer for 2-4 players, player customization, and in-game chat. It's designed to be simple to deploy and endlessly fun to play.  

---

## 🎮 Live Demo  
Play the live version here:  

https://iam-priyanshugupta.github.io/pen_fight/

---

## 📋 Table of Contents  
- [Features](#-features)  
- [Tech Stack](#️-tech-stack)  
- [How to Play](#-how-to-play)  
- [Online Multiplayer Guide](#-how-to-play-with-friends-online-multiplayer)  
- [Project Structure](#-project-structure)  
- [Security Overview](#-security-overview)  
- [How to Deploy Your Own Version](#-how-to-deploy-your-own-version)  
- [License](#-license)  

---

## ✨ Features  
- **Real-Time Online Multiplayer**: Play with 2-4 friends from anywhere using a simple Game ID system.  
- **Solo Mode vs. AI**: Challenge a computer-controlled opponent in a 1v1 duel.  
- **Player Customization**: Choose your display name and pen color.  
- **Live In-Game Chat**: Chat in real-time with opponents.  
- **Realistic Physics Engine**: Powered by **Matter.js** with point-of-impact physics.  
  - Flicking the tip of the pen causes it to spin wildly for powerful, unpredictable shots.  
  - Pushing the center of the pen results in a more stable, straight shot.  
- **On-Screen Notifications**: Instant feedback when a player is knocked out.  
- **Fully Responsive**: Play seamlessly on desktop, tablet, and mobile.  

---

## 🛠️ Tech Stack  
- **Frontend**: HTML5 + Tailwind CSS (via CDN)  
- **Physics Engine**: Matter.js  
- **Backend & Real-Time Database**: Google Firebase  
  - **Firestore Database**: Syncs game state, lobbies, and chat in real-time.  
  - **Anonymous Authentication**: Secure sign-in without accounts.  

---

## 🎮 How to Play  
### Objective  
Be the last pen on the table! Use your turn to flick your pen and knock opponents out of the arena.  

### Controls  
1. Wait for your turn (highlighted at the top).  
2. Click and hold on your pen.  
3. Drag away from the direction you want to shoot.  
   - A line shows trajectory & power.  
4. Release to launch your pen!  

---

## 🌐 How to Play with Friends (Online Multiplayer)  
1. **Share the Link**: Everyone opens the same game link.  
2. **Create a Game**: One player selects number of players (2–4).  
3. **Customize Your Pen**: Enter your name & pick a color in the lobby.  
4. **Share the Game ID**: Host shares unique Game ID with friends.  
5. **Join the Game**: Others paste Game ID & join.  
6. **Start Playing**: Game begins automatically once all players are ready.  

---

## 🏗️ Project Structure  
- **index.html** – entire project in a single file  
  - **HTML**: Structure for Start, Lobby, Game, End screens.  
  - **CSS**: Tailwind via CDN + custom `<style>` block.  
  - **JavaScript**: Game logic, physics, Firebase integration inside a `<script type="module">`.  

---

## 🔐 Security Overview  
- Firebase Anonymous Authentication ensures secure sign-ins.  
- Game state and chat are synced via Firestore with proper rules for real-time play.  

---

## 🚀 How to Deploy Your Own Version  
1. Clone this repository.  
2. Open `index.html` in your browser to test locally.  
3. Host on **GitHub Pages**, **Netlify**, or **Vercel** for free.  
4. Replace Firebase config with your own (from Firebase Console).  

---

## 📜 License  
This project is licensed under the **MIT License** – feel free to use, modify, and share.  

---
