# 🎉 SS UTSAV — Event Management Platform

> **We Plan. You Celebrate.**

SS UTSAV is an event management platform created to provide professional event planning and management services through a modern digital experience.

🌐 **Live Website:** https://www.ssutsav.in

---

## 📌 Project Overview

SS UTSAV is designed to help customers explore event services, understand available offerings, view previous work, and connect with the team for event requirements.

The platform provides a professional online presence for an event management business while establishing a foundation for future business and administrative workflows.

---

## ✨ Key Features

- 🏠 Professional customer-facing website
- 🎉 Event management service showcase
- 📦 Service and package presentation
- 🖼️ Event gallery
- 🔄 How It Works section
- ⭐ Customer testimonials
- 📩 Customer enquiry / quote workflow
- 📱 Responsive user interface
- 🔐 Backend API architecture
- ⚙️ Separate frontend and backend structure
- 🚀 Cloud deployment

---

## 🏗️ Architecture

```text
                    ┌──────────────────────┐
                    │      Customer        │
                    │      Browser         │
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │     SS UTSAV         │
                    │   Frontend Website   │
                    └──────────┬───────────┘
                               │
                         REST API Calls
                               │
                               ▼
                    ┌──────────────────────┐
                    │      Backend         │
                    │      FastAPI         │
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │       MySQL          │
                    │      Database        │
                    └──────────────────────┘
