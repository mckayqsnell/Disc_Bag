# Disc Bag

A work-in-progress mobile/web application to help disc golfers manage their personal “bag” of discs and receive recommendations on which disc to throw for specific holes. This README provides a high-level overview of the project’s motivation, technologies, timeline, and database schema direction.

---

## Purpose / Problem

Disc Bag aims to solve a common challenge disc golfers face: **choosing the best disc** for each hole, given the many unique obstacles, distances, and layouts on a course. Players will be able to:

1. **Upload and manage their personal bag of discs** (CRUD operations).
2. **Request recommendations** for the best disc(s) to throw on a particular hole.

In the future, the application may pull course details (e.g., distances, layouts) from external APIs or scraped data, but initial development will rely on user-provided course/hole information.

---

## Technologies

**Frontend**: 
- React (TypeScript)
- Node.js (for local dev tooling if desired)

**Backend**: 
- FastAPI (Python)
- PostgreSQL

---

## Timeline / Goals

- **3/19** - Create Database schema and set up PostgreSQL instance.
- **3/26** - Implement a basic FastAPI that connects to the DB (basic endpoints).
- **4/2** - Complete the API endpoints; begin a simple React/TypeScript frontend.
- **4/9** - Rough draft frontend to let users authenticate and upload their disc bags.
- **4/16** - Implement a basic recommendation system based on simple hole and disc attributes.

---

## Realistic Focus for the Next 4 Weeks

1. **Users and Disc CRUD**: Ensure that users can log in and manage (create, read, update, delete) their discs in the system.  
2. **Simple Recommender**: If time permits, build a proof-of-concept recommender that suggests a disc for a particular hole.  
3. **Course Data Handling**: In the future, allow the system to fetch or store course data from an external source (API or scraping).  

The primary goal is to **have something tangible**—a functioning MVP that handles user login and disc management. Further enhancements to the recommender and course data will come afterward.

---

## Why Am I Doing This?

- **Passion for Disc Golf**: This project is fueled by a genuine love for the sport.  
- **Practical Need**: Deciding which disc to throw can be tricky—having an app-based “caddy” could simplify the process.  
- **Growth in Tech**: This project provides hands-on experience with React, FastAPI, PostgreSQL, and building out a recommendation system.

---
