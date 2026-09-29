# Wanderlust DevOps Project Journal

## Project Origin

This project uses the open-source **Wanderlust** full-stack web application
as the base application.

Original repository:
https://github.com/krishnaacharyaa/wanderlust

The application was cloned rather than built from scratch. The purpose of
this project is to take the existing application and progressively apply
DevOps practices, infrastructure, automation, security, CI/CD, monitoring,
and deployment concepts around it.

---

# Day 1 — Application Baseline

## Objective

Understand the existing Wanderlust application and get the original
application running locally before making any DevOps changes.

## What We Did

- Cloned the Wanderlust repository.
- Inspected the repository structure.
- Identified the frontend and backend architecture.
- Identified the application's dependencies.
- Configured MongoDB Atlas for the database.
- Installed and verified Redis locally.
- Installed frontend and backend dependencies.
- Started the application locally.

## Current Architecture

Browser
→ React/Vite Frontend
→ Node/Express Backend
→ MongoDB Atlas

Redis is running locally and is used by the backend.

## Local Services

- Frontend: `http://localhost:5173`
- Backend: `http://localhost:8080`
- Redis: `127.0.0.1:6379`
- Database: MongoDB Atlas

## Result

The original Wanderlust application successfully runs locally.

The application currently contains no blog data, which is expected for
the current database.


