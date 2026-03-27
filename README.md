# 🤝 Friendship Partition Simulator

> **"Don't let the homeroom algorithm tear the squad apart."**

The **Friendship Partition Simulator** is a lightweight, high-performance web tool designed to help student groups navigate "friendship choice" forms. By using a circular "Daisy Chain" strategy, this tool calculates the mathematical probability of staying together based on your class's specific constraints.

[Insert Link to your GitHub Pages URL here]

---

## ✨ Features

* **Optimized Strategy Engine:** Automatically assigns picks using a circular chain to maximize "valid partitions."
* **Massive Capacity:** Built-in support for a **Max Class Size of 38**, ensuring it works for even the largest lecture halls.
* **Tactile UI:** Features a custom-synthesized mechanical "click" sound and a "Calculating..." state for a premium app feel.
* **Group Chat Ready:** One-click "Copy Strategy" button formats everyone's picks into a clean message for your group chat.
* **Privacy First:** Runs entirely in your browser. No data is ever sent to a server.

---

## 🧬 The Science

Most students fail to stay together because they all pick the same "popular" friend, creating a bottleneck that the school's sorting algorithm can't solve. 

This simulator uses a **Circular Partition Logic**:
1. It treats the group as a ring.
2. Each person picks the $N$ people directly following them in the ring.
3. This creates a "redundant web" of connections, ensuring that no matter who the computer starts with, the "validity" of the group remains intact.

---

## 🚀 How to Use

1.  **Set Your Size:** Enter the number of people in your friend group.
2.  **Apply Strategy:** Click "Apply Optimized Strategy" to see the mathematical ideal picks.
3.  **Customize:** Replace "Person 1, 2, 3..." with your friends' actual names.
4.  **Simulate:** Hit "Run Math Simulation" to see every possible room assignment the school could generate.
5.  **Share:** Click "Copy Strategy" and paste it into your group text.

---

## 🛠️ Tech Stack

* **HTML5 / CSS3** (Custom Inter font integration)
* **Vanilla JavaScript** (Recursive Partitioning Algorithm)
* **Web Audio API** (Real-time frequency synthesis for the "click" sound)

---

## 📜 Disclaimer
*This tool is for simulation purposes only. While it maximizes your mathematical odds, it cannot account for teachers who manually override the system because you guys talk too much.*
