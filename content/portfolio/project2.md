---
title: "Project 2"
description: "Laravel API, Shell Deployment, Docker Deployment, and Automated GitHub.io Publication"
date: 2025-11-30
draft: false
---

# Project 2 – Laravel API + Automated Deployment

**By:** Jacob Robbins  
**Tech Stack:** Laravel, PHP, MySQL, Postman, Docker, Shell Scripts, Hugo, GitHub Actions  
**Date:** Fall 2025  

---

## Project Overview

Project 2 builds upon Project 1 by re-implementing the same REST API, but now using **Laravel**, **Eloquent ORM**, **Docker**, **shell scripts**, and **automated GitHub.io deployment**.

This project brings an industry-level development workflow, including:  
- Laravel API Development  
- Database migrations & models  
- Automated deployment (shell scripts + Docker)  
- Documentation with Hugo  
- GitHub Actions CI/CD for GitHub Pages hosting

---

# Re-Implement Project 1 APIs (Laravel)

This phase recreates your Project 1 gaming API using Laravel.

### Technologies Used
- **Laravel 11**
- **Laravel Sanctum** (token authentication)
- **Eloquent ORM**
- **MySQL**
- **Postman** (API testing)

---

## API Endpoints Re-Implemented

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | /auth/register | Register new user |
| POST | /auth/login | Login & receive token |
| GET | /players | Get all players |
| GET | /players/{id} | Get one player |
| GET | /games | List all games |
| GET | /leaderboard/{gameId} | Get leaderboard |

---

##  Authentication (Sanctum)

Sanctum was added to protect sensitive routes:

```php
Route::middleware('auth:sanctum')->group(function () {
  Route::get('/players', [PlayerController::class, 'index']);
});
