# 🏓 PongPal – Softhouse Ping Pong Booking App

**PongPal** is an internal project developed at **Softhouse Karlskrona**.  
Its main goal is to digitalize and simplify how employees manage the office ping-pong table from booking and playing to tracking results and leaderboards.

This repository contains **only visual and video documentation** of the project.  
🖼️ No source code is included here due to internal policies.

---

## 🎥 Demo Videos

Here are the three main demo recordings, each focusing on a different part of the system 👇

### 🌐 Website Demo
▶ [Watch Website Demo](https://drive.google.com/file/d/1lHuSnqc1bbySRdiwSJK6r0idp7MAXM9q/view?usp=sharing)

> In this video, I demonstrate the **web application interface** — showing how users log in, view the homepage, explore the “About” page, and check statistics.  
> You’ll see how employees can book a table, view the booking calendar, and navigate between pages such as **Home**, **About**, **Bookings**, and **Profile**.  
> The goal is to make everything easy, visual, and accessible directly in the browser.

---

### 🛠️ Admin Demo
▶ [Watch Admin Demo](https://drive.google.com/file/d/1sXilTbFCk86BoB-YuWdxKeZszTA3YSEJ/view?usp=sharing)

> This demo focuses on the **Admin functionality** of PongPal.  
> Here I show how an administrator can manage the system, including turning the **Raspberry Pi camera on or off**, viewing user statistics, and monitoring active bookings.  
> The Admin view includes extra options hidden from regular users, ensuring secure and controlled access.

---

### 💬 Slack Command Demo
▶ [Watch Slack Command Demo](https://drive.google.com/file/d/1jXokLO80PFTQn7WlYOMAsUHlBBNEaA35/view?usp=sharing)

> In this video, I demonstrate the **Slack integration** and explain each command in detail.  
> Commands include:
> - `/pingis status` → checks if the table is free or occupied  
> - `/pingis book <date> <time>` → books a 30-minute slot  
> - `/pingis update` → updates a booking  
> - `/pingis delete` → cancels a booking  
> - `/pingis report` → reports a match result  
> - `/pingis toplist` → shows the monthly leaderboard  
> - `/pingis statistics` → displays personal stats and win rate  
>
> You’ll also see how Slack responds in real time — confirming bookings, showing results, and updating Firestore.

---

## 🧩 System Overview

| Component | Description | Technology |
|------------|-------------|-------------|
| 💬 **Slack App** | Handles commands, challenges, and result reporting | Slack API + Firebase Functions |
| 🌐 **Web Interface** | Booking, statistics, and user profiles | React + TypeScript |
| 🔥 **Backend** | Database, logic, and authentication | Firebase Firestore + Cloud Functions |
| 📷 **Raspberry Pi Camera** | Detects table activity, toggled by admin | Python + Firebase Realtime |
| 🔐 **Authentication** | Google OAuth for secure logins | Google Identity Platform |

---

## 🧠 Project Purpose

🎯 **Goal:**  
To build a connected, interactive system that encourages employees to play more, compete fairly, and have fun — all while learning teamwork and automation technologies.

💡 **Key Outcomes:**
- Fully integrated booking system through Slack and web  
- Real-time match reporting and ranking system  
- Automated camera control and table-status detection  
- Clean, modern user interface for both employees and admins  
- A great example of combining **software engineering**, **UX**, and **IoT**

---

## 📸 Screenshots

*(Images are located in the `/images` folder and visually document each main page of the app.)*

### 🏠 Home Page
> Displays the Softhouse logo, a short welcome message, and live statistics about total matches and top players of the month.

### ℹ️ About Page
> Explains how PongPal works and the overall goal — digitalizing the office ping-pong experience.

### 📅 Booking Calendar
> Shows available and booked time slots.  
> Blue = booked, Green = available.  
> Users can easily select their preferred day and time.

### 👤 Profile Page
> Displays player statistics — total matches, wins, losses, win rate, and a match history table.

---

## 🚀 Summary

PongPal connects people, data, and fun.  
It combines **Slack automation**, **Firebase backend**, and **React frontend** into a single ecosystem.  
The project demonstrates real-world engineering skills: structured code, modular design, and seamless integration between multiple platforms.

---

## ⚠️ Note

This repository contains **no source code** only presentation materials (images and videos).  
The full implementation is used internally by **Softhouse**.

---

© 2025 PongPal – A Softhouse Intern Project 💼
