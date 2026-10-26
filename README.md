

# 🏓 PickleQ Web – Court Rotation & Queue Manager

A sleek, responsive, single-file web application for managing open play, player queues, court rotations, and match stats for pickleball clubs, recreation centers, and informal groups.

Inspired by rotation tools like **PickleQ**, this application simplifies court assignments, handles rotation logic, keeps track of player stats, and includes court-side display features with voice callouts.

---

## ✨ Features

* **📊 Active Courts Dashboard**
* Live count-up timers for match duration.
* Court status indicators (*Available*, *Warm-Up*, *In Progress*).
* Quick action to input final scores and complete matches.


* **👥 Queue Management & "Up Next" Deck**
* **Up-Next Banner**: Displays the exact 4 players lined up for the next open court.
* **Player Status**: Toggle players between *Active* and *Resting* without removing them from the queue.
* **Skill Badges**: Assign skill levels (Beginner, Intermediate, Advanced) to ensure balanced groups.
* **Quick Add**: Add single players or batch-add groups of 4.


* **⚙️ Dynamic Rotation Engines**
* **4 In / 4 Out**: Standard open-play rotation (all 4 players step off after a match).
* **2 In / 2 Out (Winners Stay & Split)**: Winners remain on court and split up; 2 new players enter from the queue.
* **Skill-Based Matching**: Groups players by compatible skill levels.


* **📺 Court-Side / TV Display Mode**
* Full-screen high-contrast presentation view optimized for iPad, tablet, or TV screens placed at the court entrance.


* **🔊 Voice Callouts & Audio Cues**
* Automated Web Speech API voice announcements calling players to their assigned court (e.g., *"Court 1 is ready for Sarah, Mike, Alex, and John!"*).


* **📈 Stats & Analytics**
* Tracks total matches played per player, wins/losses, and total time on court.


* **💾 Local Storage Persistence**
* Automatically saves players, active court states, match history, and configurations to `localStorage`.



---

## 🚀 Getting Started

### Prerequisites

No backend or build tools required. The application runs entirely in any modern web browser.

### Installation & Running

1. Clone or download the source files.
2. Open `index.html` in your browser (Google Chrome, Safari, Edge, or Firefox).

---

## 🛠️ Usage Guide

1. **Setup Courts**: Add the number of active courts available at your venue.
2. **Add Players**: Enter player names and set their skill level (1.0 to 5.0).
3. **Auto-Assign / Start Match**: Click **"Fill Open Courts"** or drag/assign players to send the top 4 queued players to an available court.
4. **Complete Match**: Click **"Finish Match"** on an active court card, optionally enter the final score, and confirm. The app automatically pushes the players back into the rotation based on your selected rule set (*4 In/4 Out*, *2 In/2 Out*, etc.).
5. **Launch TV Mode**: Click **"TV Display Mode"** on top of the dashboard for an automated, clean view suitable for wall mounting.

---

## 💻 Tech Stack

* **HTML5 & CSS3** (CSS Grid, Flexbox, CSS Custom Properties)
* **Vanilla JavaScript (ES6+)**
* **Web Speech API** (For audio announcements)
* **HTML5 LocalStorage** (For offline data persistence)

---

## 📄 License

Distributed under the MIT License. Feel free to modify and adapt for your local pickleball group or venue!
