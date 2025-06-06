# System Architecture for Pentest CTF Platform

## 1. Overview
A CTF platform with React frontend, Node.js/Express backend, PostgreSQL database, and Docker containers, deployed on Kali Linux.

## 2. Components
- **Frontend (React)**:
  - Pages: Home, Challenges, Leaderboard, Submit Flag.
  - Libraries: Axios, Tailwind CSS.
- **Backend (Node.js/Express)**:
  - Endpoints: /register, /login, /challenges, /submit-flag.
  - Authentication: JWT.
- **Database (PostgreSQL)**:
  - Tables: users, challenges, submissions.
- **Docker**:
  - Isolated containers for challenges (e.g., SQL Injection, Buffer Overflow).
- **Deployment**: Kali Linux with Nginx for HTTPS.

## 3. Workflow
1. User registers/logs in via frontend.
2. Frontend fetches challenges from backend API.
3. User interacts with Dockerized challenge environments.
4. User submits flags to backend for validation.
