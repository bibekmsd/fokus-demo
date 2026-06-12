# Fokus 🎯

<div align="center">

### Stay Focused. Build Consistency. Achieve More.

A modern productivity application built with Flutter that helps users manage daily missions, track habits, maintain streaks, and visualize progress through insightful analytics.

[![Platform](https://img.shields.io/badge/Platform-Flutter%20%7C%20Dart-02569B?logo=flutter&logoColor=white)](https://flutter.dev)
[![Architecture](https://img.shields.io/badge/Architecture-MVC-green)](#-architecture)
[![Status](https://img.shields.io/badge/Google%20Play-Coming%20Soon-orange?logo=google-play&logoColor=white)](#-availability)

</div>

---

## 📱 Screenshots Gallery

<div align="center">
<table>
  <tr>
    <td align="center"><b>Login</b></td>
    <td align="center"><b>Dashboard</b></td>
    <td align="center"><b>Add Missions</b></td>
  </tr>
  <tr>
    <td><img src="https://kcm7tq9i12.ufs.sh/f/pJziTprsGA5mAITsHkhKnIJrSwlyegtNUuWOPa0Dz6qmCvVj" max-height="320px" alt="Login"/></td>
    <td><img src="https://kcm7tq9i12.ufs.sh/f/pJziTprsGA5mAd6n0LhKnIJrSwlyegtNUuWOPa0Dz6qmCvVj" max-height="320px" alt="Dashboard"/></td>
    <td><img src="https://kcm7tq9i12.ufs.sh/f/pJziTprsGA5mjoRcUjXLoRXyskKNlcOh8wAuYEt6baCHIPiQ" max-height="320px" alt="Add Missions"/></td>
  </tr>
  <tr>
    <td align="center"><b>My Tasks (Today)</b></td>
    <td align="center"><b>Completed Tasks</b></td>
    <td align="center"><b>Routine</b></td>
  </tr>
  <tr>
    <td><img src="https://kcm7tq9i12.ufs.sh/f/pJziTprsGA5mudibzuN9jWKdpPAfgr0khw6JNbaDFveLUsxZ" max-height="320px" alt="Today Missions"/></td>
    <td><img src="https://kcm7tq9i12.ufs.sh/f/pJziTprsGA5mTJeCoLcLYy8DKQ3aR5t2cPexSjsgbABJ71iw" max-height="320px" alt="Completed Tasks"/></td>
    <td><img src="https://kcm7tq9i12.ufs.sh/f/pJziTprsGA5mDdnBykpu2NZej17c3HInterT5VIkY9PiyJ" max-height="320px" alt="Routine"/></td>
  </tr>
  <tr>
    <td align="center"><b>Calendar</b></td>
    <td align="center"><b>Life Tracker (Monthly)</b></td>
    <td align="center"><b>Life Tracker (Yearly)</b></td>
  </tr>
  <tr>
    <td><img src="https://kcm7tq9i12.ufs.sh/f/pJziTprsGA5mEAe6GmnJOBT83LFgp40SuHYjxv7nVsZCNqcX" max-height="320px" alt="Calendar"/></td>
    <td><img src="https://kcm7tq9i12.ufs.sh/f/pJziTprsGA5mZ835L9klTZa7g9i5Cm3SsKNy8HYewnthv0R2" max-height="320px" alt="Monthly Calendar"/></td>
    <td><img src="https://kcm7tq9i12.ufs.sh/f/pJziTprsGA5mW6jmNuLc1f3rxiDUHZsLbIKe09n2zuW5otQj" max-height="320px" alt="Yearly Calendar"/></td>
  </tr>
  <tr>
    <td align="center" colspan="3"><b>Profile</b></td>
  </tr>
  <tr>
    <td align="center" colspan="3"><img src="https://kcm7tq9i12.ufs.sh/f/pJziTprsGA5mnFPqpG7rMumseGiHLxEFCPR8vZ1lJ7w0DYX9" max-height="320px" alt="Profile"/></td>
  </tr>
</table>
</div>

---

## ✨ Features

* **🎯 Daily Mission Management**
    * Create and manage daily missions with sleek UI interactions.
    * Organize and track progress metrics dynamically.
* **📅 Calendar & Life Tracking**
    * Beautiful visual history maps to keep track of completed tasks.
    * Comprehensive breakdown over months and years.
* **🔥 Habit Formation & Streaks**
    * Gamified streak system designed to maintain long-term consistency.
    * Milestone tracking with unlockable achievements and badges.
* **📊 Productivity Analytics**
    * Get precise breakdowns of daily and weekly completion rates.
* **🎨 True Adaptable UI**
    * Full support for unified Dark & Light themes with high-performance responsive components.

---

## 🛠 Tech Stack

| Category | Technologies |
|:---|:---|
| **Framework** | Flutter |
| **Language** | Dart |
| **State Management** | GetX |
| **Backend / Auth** | Firebase Suite |
| **Database** | PostgreSQL |
| **Architecture** | MVC (Model-View-Controller) |
| **Version Control** | Git & GitHub |

---

## 🏗 Architecture

Fokus relies on a highly scalable, isolated **MVC Pattern** to separate logic layers efficiently:

```directory
lib/
├── models/        # Data layout blueprints and parsing
├── controllers/   # GetX lifecycle states and operational logic
├── views/         # High-fidelity visual components
│   ├── screens/   # Standalone view pages
│   └── widgets/   # Globally reusable atomic UI components
├── services/      # Cloud APIs, Firebase actions, and DB connections
├── routes/        # Main application routing maps
├── utils/         # Enums, app constants, and custom themes
└── main.dart      # Application bootstrapper
