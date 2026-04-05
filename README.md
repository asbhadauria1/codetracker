# ⚡ CodeTracker · The Competitive Intelligence Hub

> **Real-time Codeforces analytics — visualize your coding journey like never before.**

[![React](https://img.shields.io/badge/React-18.x-61DAFB?logo=react)](https://reactjs.org/)
[![Codeforces](https://img.shields.io/badge/Codeforces-API-1F8ACB?logo=codeforces)](https://codeforces.com/apiHelp)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

---

## 🚀 Overview

**CodeTracker** is a sleek, real-time analytics dashboard for Codeforces users. It transforms raw API data into meaningful insights — from contest history to tag-wise problem breakdowns. Built with React and the official Codeforces API, it's designed for developers who want to track their competitive programming progress beautifully.

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 🧑‍💻 **User Info** | Name, rating, rank, location, organization, friends count |
| 🏆 **Best Contest Rank** | Your most impressive contest performance |
| 📘 **Last Solved Problem** | Direct link + problem tags |
| 📊 **Total Problems Solved** | Unique problem count across all submissions |
| 🏷️ **Tag-wise Breakdown** | Visual map of problems solved by topic (DP, Graphs, etc.) |
| 🔍 **Search Any Handle** | Just type and hit search — instant insights |

---

## 🖼️ Preview

```
┌─────────────────────────────────────────────────────────┐
│ 🔍 [ Enter User ID ] [ Search ]                        │
├─────────────────────────────────────────────────────────┤
│ 👤 User Image                                          │
│ Name: Aditya                                           │
│ From: Delhi, India                                     │
│ Current Rating: 1612 (specialist)                      │
│ Best Rank: 42 in Codeforces Round #927                 │
│ Last Problem Solved: 1791C - Prepend and Append        │
│ Total Solved: 347                                      │
│ Tags: DP: 45, Graphs: 32, Greedy: 67 ...               │
└─────────────────────────────────────────────────────────┘
```

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-------------|
| Frontend | React 18 |
| Styling | CSS3 (custom) |
| API | Codeforces Official API |
| State | React Hooks (useState, useEffect) |
| Build Tool | Parcel / Webpack |

---

## 📦 Installation & Setup

```bash
git clone https://github.com/yourusername/codetracker.git
cd codetracker
npm install
npm start
```

> Make sure you have Node.js (v14+) installed.

---

## 🔗 API Endpoints Used

| Endpoint | Purpose |
|----------|--------|
| user.info?handles= | Fetch user profile |
| user.rating?handle= | Get contest history & best rank |
| user.status?handle= | Retrieve submissions & solved problems |

---

## 🚧 Future Improvements

- Chart.js integration for rating history graph  
- Compare two users side-by-side  
- Dark mode toggle  
- Export stats as PDF  
- Solved problems calendar heatmap  

---