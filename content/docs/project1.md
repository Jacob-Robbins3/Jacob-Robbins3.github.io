---
title: "Project 1"
marp: true
theme: default
class: lead
paginate: true
---



# 🎮 Game API Project

**By:** Jacob Robbins  
**Tech Stack:** PHP, NGINX, MySQL, Postman  
**Date:** October 2025

---

## Overview

This project is a RESTful API for a gaming platform.  
It allows users to:
- Register and login
- View player stats
- Fetch game data
- Access leaderboards

---

## Tools & Technologies

- **PHP** — backend logic and database operations  
- **MySQL** — player and game data  
- **NGINX** — web server handling API requests  
- **Postman** — endpoint testing  
- **GitHub** — version control and hosting

---

## API Endpoints

| Method | Endpoint | Description |
|--------|-----------|-------------|
| POST | /auth/register | Register a new user |
| POST | /auth/login | Authenticate a user |
| GET | /players | Retrieve all players |
| GET | /players/:id | Retrieve a specific player |
| GET | /games | Get list of all games |
| GET | /leaderboard/:gameId | Fetch game leaderboard |

---

## Authentication

Users receive a **JWT token** upon login.  
Include it in headers for protected endpoints:

PROJECT 2

Finished all the following below in order:

- **Re-implement Project 1 APIs**: 20%
  - Re-implement Project 1 endpoints using Laravel  
  - Use Eloquent ORM for database operations  
  - Implement authentication with Laravel Sanctum  

- **Deploy with a shell script**: 20%
  - Automated deployment using shell script
  - Create run script (`run.sh`) for one-command deployment  
  - Use existing shell script to make a shell script for your Laravel project.


- **Deploy with Docker**: 20%
  - Containerize with Docker & Docker Compose  
  - Create setup script (`setup.sh`) for one-command deployment  
  - Use existing shell script to make a shell script for your Docker project.

- **Re-implement Project 1 Documentation**: 20%
  - Re-implement Project 1 marp documentation using Hugo
  - Both Marp and Hugo use Markdown, so minimal (or no) efforts should be required to transform.
  - Add your portpolio pages to Hugo.

- **Automatic Deploy to GitHub.io**: 20%
  - Publish documentation to **GitHub.io**  
  - Upload complete source to **GitHub** so GitHub action transforms the source into published website to GitHub.io.

I had some difficulties with re-implementing Project 1 API's but I got it to work by looking over the class material again for a refresher. Other than that everything wasn't super hard.
Github is confusing sometimes but that't about it.

