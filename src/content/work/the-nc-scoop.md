---
title: The NC Scoop
publishDate: 2025-03-20 00:00:00
img: /assets/TheNCScoop.png
img_alt: A clean news app interface displaying headlines, articles, and categories
description: |
  A full-stack news platform built with React and Express, offering live article browsing, comment interaction, and user management.
tags:
  - React
  - Express
  - PostgreSQL
  - TDD
---

> A news app for staying informed — and staying curious.

The NC Scoop is a full-stack news aggregation platform where users can browse, sort, and interact with curated articles. Built with **React**, **Express**, and **PostgreSQL**, it features a robust API backend, full CRUD functionality, and a responsive front-end UI.

Users can view news by topic, read full articles, sort by popularity or date, and engage in comment threads. The site also supports user authentication, individual user pages, and seamless navigation through client-side routing.

---

### Features

- Browse articles by topic or popularity
- Read full articles with live comment sections
- Sort and filter content by date or votes
- Leave and delete comments (if logged in)
- Navigate through an intuitive, responsive UI

---

### Technical Approach

The backend was built using **Express** with a RESTful API structure and **PostgreSQL** for data persistence. Strong emphasis was placed on **Test Driven Development (TDD)** using **Jest** and **Supertest** to ensure a reliable, predictable experience.

The frontend consumes the API using **Axios** and handles state management, routing, and user interaction entirely on the client side. Pagination, dynamic sorting, and error handling help create a polished UX.

---

### Tech Highlights

- Fully tested backend using **Jest** and **Supertest**
- RESTful API with layered error handling and modular architecture
- Dynamic client-side routing using **React Router**
- PostgreSQL database optimized for relationships between users, articles, and comments
- Responsive design, deployed to **Render** and **Netlify**
