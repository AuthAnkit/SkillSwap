# 💡 Skill Swap Platform

## 📌 Problem Statement

In today's world, many people possess valuable skills but lack access to formal exchanges or learning networks. For example, someone may know Photoshop but want to learn Excel, while another may know Excel and want to learn Photoshop. However, there is **no easy or structured way to connect individuals for a fair exchange of skills**.

**Goal:**  
Build a platform where users can **list their own skills** and **request others in return**, enabling **peer-to-peer learning and collaboration** without the need for money or formal credentials.

---

## ✅ Proposed Solution

The **Skill Swap Platform** is a full-stack web application that allows users to:

- Create a personal profile
- List skills they **offer** and **want**
- Browse and search for matching users
- **Request skill swaps**, **accept or reject offers**
- **Rate** each other after a swap
- Let administrators monitor and manage platform activity

This creates a **mutual learning ecosystem** where knowledge is freely exchanged.

---

## 🎯 Key Features

### 👤 User Features

- Register/login/logout
- Update personal profile (name, location, photo)
- Add skills offered & skills wanted
- Set availability (Weekends, Evenings, etc.)
- Set profile as Public/Private
- Search users by skill (e.g., “Photoshop”)
- Send/accept/reject/delete skill swap requests
- Leave a rating or feedback after a swap

### 🛠️ Admin Features

- View and moderate user skill listings
- Reject inappropriate or spammy descriptions
- Ban users who violate policies
- Monitor all pending/accepted/cancelled swaps
- Send platform-wide messages (e.g., downtime notices)
- Download user activity, feedback logs, and swap statistics

---

## 🛠️ Tech Stack

| Layer         | Technology Used                  |
|---------------|----------------------------------|
| Frontend      | HTML, CSS (Bootstrap), EJS       |
| Backend       | Node.js, Express.js              |
| Database      | MongoDB                          |
| Authentication| Express-Session (Basic Session)  |
| Deployment    | Localhost (with option for Render/Heroku) |

---

## 📂 Folder Structure

