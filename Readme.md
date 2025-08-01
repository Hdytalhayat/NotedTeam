# 📝 NotedTeam – Collaborative Todo List App

> **Short Description:**  
NotedTeam is a collaborative todo list app designed to simplify team workflows. It is built using Flutter for the frontend and Golang for the backend.

---

## 📁 Repositories

- [GitHub Frontend](https://github.com/Hdytalhayat/NotedTeam-Flutter) (Try NotedTeam App)
- [GitHub Backend](https://github.com/Hdytalhayat/NotedTeam-Go)
- [NotedTeam Page](https://Hdytalhayat.github.io/NotedTeam)

---

## 📌 Key Features

| Feature | Description |
|--------|-------------|
| ✅ Todo List | Users can create daily task lists for personal or team use. |
| 👥 Sharing Editor | Todos can be shared with a team for collaborative editing. |
| 🔄 Task Status | Each task has a status: `Pending`, `Working`, `Completed`. |
| 🔥 Urgency Labels | Tasks can be labeled with urgency: `Low`, `Medium`, `High`. |
| 📱 Flutter UI | Mobile-first user interface built with Flutter. |
| 🖥️ Golang Backend | Backend REST API built using Go. |

---

## 🗂️ Project Structure

### 📦 Backend (Golang)
- Framework: `gin-gonic` or `fiber`
- Database: PostgreSQL / SQLite
- Features:
  - CRUD API endpoints for todo tasks
  - User authentication
  - Collaboration endpoints (invites, edit access)
  - Status and urgency as enums
  - Authorization middleware

### 📱 Frontend (Flutter)
- Framework: Flutter
- State Management: `provider` or `riverpod`
- UI Features:
  - Todo list with status & urgency filters
  - Optional real-time collaborative interface
  - Clean, intuitive design

---

## 🔁 Workflow Overview

1. User registers or logs in
2. Creates a todo project
3. Invites team members to the project
4. Adds tasks
5. Sets status and urgency
6. Collaborates to complete the tasks

---

## ✅ Task Status

| Status | Color | Description |
|--------|-------|-------------|
| Pending | 🟡 Yellow | Newly created and not yet started |
| Working | 🔵 Blue | Currently in progress by a team member |
| Completed | ✅ Green | Task has been finished |

---

## 🚨 Urgency Levels

| Urgency | Color | Description |
|---------|-------|-------------|
| Low | 🟢 Green | Not urgent |
| Medium | 🟠 Orange | Moderately important |
| High | 🔴 Red | Highly urgent |

---

## 🗓️ Development Roadmap

| Phase | Description | Status |
|-------|-------------|--------|
| Phase 1 | Backend & DB setup + user login | ✅ Completed |
| Phase 2 | CRUD todo + status management | ✅ Completed |
| Phase 3 | Collaboration (user invitations) | ✅ Completed |
| Phase 4 | Real-time sync | ✅ Completed |
| Phase 5 | Publish to Play Store | ⏳ Upcoming |

---

## 🔐 Technology Stack

| Layer | Technology |
|-------|------------|
| Frontend | Flutter |
| Backend | Golang |
| Database | MySQL |
| API Auth | JWT (JSON Web Token) |
| Hosting | Railway |

---
