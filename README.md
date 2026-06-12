# Fokus 🎯

<div align="center">

### Stay Focused. Build Consistency. Achieve More.

A modern productivity application built with Flutter that helps users manage daily missions, track habits, maintain streaks, and visualize progress through insightful analytics.

[![Platform](https://img.shields.io/badge/Platform-Flutter%20%7C%20Dart-02569B?logo=flutter&logoColor=white)](https://flutter.dev)
[![Architecture](https://img.shields.io/badge/Architecture-MVCS-green)](#-architecture)
[![Status](https://img.shields.io/badge/Google%20Play-Coming%20Soon-orange?logo=google-play&logoColor=white)](#-availability)

</div>

---

## 📱 Screenshots Gallery

<div align="center">
<table>
  <tr>
    <td align="center" width="33%"><b>Login</b></td>
    <td align="center" width="33%"><b>Dashboard</b></td>
    <td align="center" width="33%"><b>Add Missions</b></td>
  </tr>
  <tr>
    <td align="center"><img src="https://kcm7tq9i12.ufs.sh/f/pJziTprsGA5mAITsHkhKnIJrSwlyegtNUuWOPa0Dz6qmCvVj" height="320" alt="Login"/></td>
    <td align="center"><img src="https://kcm7tq9i12.ufs.sh/f/pJziTprsGA5mAd6n0LhKnIJrSwlyegtNUuWOPa0Dz6qmCvVj" height="320" alt="Dashboard"/></td>
    <td align="center"><img src="https://kcm7tq9i12.ufs.sh/f/pJziTprsGA5mjoRcUjXLoRXyskKNlcOh8wAuYEt6baCHIPiQ" height="320" alt="Add Missions"/></td>
  </tr>
  <tr>
    <td align="center"><b>My Tasks (Today)</b></td>
    <td align="center"><b>Completed Tasks</b></td>
    <td align="center"><b>Routine</b></td>
  </tr>
  <tr>
    <td align="center"><img src="https://kcm7tq9i12.ufs.sh/f/pJziTprsGA5mudibzuN9jWKdpPAfgr0khw6JNbaDFveLUsxZ" height="320" alt="Today Missions"/></td>
    <td align="center"><img src="https://kcm7tq9i12.ufs.sh/f/pJziTprsGA5mTJeCoLcLYy8DKQ3aR5t2cPexSjsgbABJ71iw" height="320" alt="Completed Tasks"/></td>
    <td align="center"><img src="https://kcm7tq9i12.ufs.sh/f/pJziTprsGA5mDdnBykpu2NZej17c3HqzRMCt8T5VIkY9PiyJ" height="320" alt="Routine"/></td>
  </tr>
  <tr>
    <td align="center"><b>Calendar</b></td>
    <td align="center"><b>Life Tracker (Monthly)</b></td>
    <td align="center"><b>Life Tracker (Yearly)</b></td>
  </tr>
  <tr>
    <td align="center"><img src="https://kcm7tq9i12.ufs.sh/f/pJziTprsGA5mEAe6GmnJOBT83LFgp40SuHYjxv7nVsZCNqcX" height="320" alt="Calendar"/></td>
    <td align="center"><img src="https://kcm7tq9i12.ufs.sh/f/pJziTprsGA5mZ835L9klTZa7g9i5Cm3SsKNy8HYewnthv0R2" height="320" alt="Monthly Calendar"/></td>
    <td align="center"><img src="https://kcm7tq9i12.ufs.sh/f/pJziTprsGA5mW6jmNuLc1f3rxiDUHZsLbIKe09n2zuW5otQj" height="320" alt="Yearly Calendar"/></td>
  </tr>
  <tr>
    <td align="center" colspan="3"><b>Profile and Settings</b></td>
  </tr>
  <tr>
    <td align="center" colspan="3">
      <img src="https://kcm7tq9i12.ufs.sh/f/pJziTprsGA5mnFPqpG7rMumseGiHLxEFCPR8vZ1lJ7w0DYX9" height="320" alt="Profile"/>
      &nbsp;&nbsp;&nbsp;&nbsp;
      <img src="https://kcm7tq9i12.ufs.sh/f/pJziTprsGA5mXMjCsfQzI78T9nX5CYkVuEiWwLAeqf60lorR" height="320" alt="Settings"/>
    </td>
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
| **Backend / Auth** | Nodejs & Firebase |
| **Database** | PostgreSQL |
| **Architecture** | MVCS (Model-View-Controller-Service) |
| **Version Control** | Git & GitHub |

---

## 🏗 Architecture

Fokus relies on a highly scalable, isolated **MVC Pattern** to separate logic layers efficiently:

```directory
lib/
fokus_new/lib/
├── models/               ← M (Models)
├── controllers/          ← C (Controllers) - GetX state management
├── modules/              ← V (Views) - Feature-based organization
│   ├── home/
│   ├── settings/
│   ├── missions/
│   └── profile/
├── services/             ← S (Services) - Business logic & API calls
│   ├── mission_sync_service.dart
│   ├── routine_sync_service.dart
│   ├── network_service.dart
│   └── local_notification_service.dart
├── core/                 ← Core layer (Repositories, Local DB)
│   ├── api/              ← API repositories
│   └── local/            ← Hive database
├── repositories/         ← Repository pattern for data access
├── widgets/              ← Reusable UI components
└── utils/                ← Helpers & constants

