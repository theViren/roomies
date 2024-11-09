# 🗨️ Roomies - Instant Group Chat Application

**Roomies** is an instant group chat app built with Node.js, Next.js, Supabase (for PostgreSQL), Redis, and Prisma. The application allows users to create chat rooms, set passcodes for secure access, and invite others to join via a unique room URL. With Google Sign-In, users can easily register and manage rooms, making it easy to chat and connect with friends or teams.

---

## 📜 Table of Contents
- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Setup and Installation](#-setup-and-installation)
---

## ✨ Features
- **User Authentication**: Quick login using Google Sign-In.
- **Create and Manage Rooms**: Users can create rooms, set a passcode, and manage (edit/delete) them.
- **Secure Room Access**: Share a room URL and passcode to allow others to join securely.
- **Real-time Chat**: Chat within rooms with real-time messaging using Socket.IO.
- **Scalable and Efficient**: Redis is used with Socket.IO for handling real-time connections efficiently.

---

## 🛠 Tech Stack
- **Frontend**: Next.js
- **Backend**: Node.js, Express
- **Database**: PostgreSQL (via Supabase), Prisma ORM
- **Socket Communication**: Socket.IO with Redis
- **Authentication**: Google Sign-In
- **Deployment**: Vercel, Heroku, or similar platforms

---

## 🚀 Setup and Installation

### Prerequisites
- [Node.js](https://nodejs.org/) installed
- [Supabase](https://supabase.io/) account and PostgreSQL setup
- [Redis](https://redis.io/) setup (locally or managed)

### Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/theViren/roomies.git
   cd roomies
