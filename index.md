---
layout: default
title: "TinyChat Devlog"
---

# 👋 Welcome to TinyChat Devlog

This is the development blog of my most ambitious project so far — **TinyChat**.
A lightweight, real-time chat application built with passion and curiosity.

## 🧠 About the Project

TinyChat is a personal journey into building a full-stack web application with real-time capabilities, user authentication, and clean architecture. It's made with:

- 🌐 Frontend: HTML + JS + PHP
- 🔧 Backend: FastAPI (Python)
- 💬 WebSocket Server: Python
- 🗄️ Database: SqLite3

## 📅 Devlog

All development updates will be posted here. Stay tuned for progress, pitfalls, and breakthroughs.

---

## 📬 Latest Blog Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> <small>({{ post.date | date: "%Y-%m-%d" }})</small>
    </li>
  {% endfor %}
</ul>

---

Made with ❤️ by Kamakosan  AKA attila00198
*August 08, 2025*
