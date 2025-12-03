+++
title = "Project 1 – Game API"
description = "RESTful game API created using PHP, MySQL, and NGINX."
+++

# 🎮 Game API Project

**Tech Stack:** PHP, MySQL, NGINX, Postman  
**Date:** October 2025  
**Author:** Jacob Robbins

## Overview

This project is a RESTful API for a gaming platform.  
It allows users to:

- Register and log in  
- View player stats  
- Fetch game data  
- Access leaderboards  

## Tools Used

- PHP  
- NGINX  
- MySQL  
- Postman  
- Git/GitHub

## Endpoints

| Method | Endpoint | Description |
|--------|-----------|-------------|
| POST | /auth/register | Create a new user |
| POST | /auth/login | User login |
| GET | /players | All players |
| GET | /players/:id | Specific player |
| GET | /games | Game list |
| GET | /leaderboard/:gameId | Game leaderboard |

## Authentication

The API uses **JWT tokens** for secure login.

Include in headers: Bearer <token>


## Summary

This project demonstrates:

- Secure authentication  
- REST API design  
- SQL database integration  
- JSON responses  
- NGINX server configuration  


