🌐 [Português (BR)](README.pt_BR.md) | [Español](README.es.md)

# Soc Ops

**Soc Ops** is a playful social bingo app built for in-person team mixers and event icebreakers. Challenge your group to find people who match the prompts, then race to complete 5 in a row.

> A lightweight Spring Boot game experience with a clean web UI and a hands-on workshop guide for building collaborative apps.

---

## ✨ Why this project?

- **Interactive icebreakers** for meetups, workshops, and team-building events
- **Easy deployment** with Maven and a small Spring Boot backend
- **Designed for learning**, with workshop content documenting design, agent workflows, and frontend experience
- **Multilingual landing page** support in Portuguese and Spanish

---

## 🚀 Quick start

```bash
cd socops
./mvnw spring-boot:run
```

Then open `http://localhost:8080` in your browser.

---

## 💡 Features

- Social bingo game board for real-world icebreaker activities
- Simple web-based experience using Spring Boot templates and static assets
- Build-ready Java app with included Maven Wrapper
- Workshop-driven learning path for development and collaboration

---

## 🧭 Workshop guide

Follow the step-by-step lab to explore project architecture, frontend design, and multi-agent development.

| Part | Title |
|------|-------|
| [**00**](workshop/00-overview.md) | Overview & Checklist |
| [**01**](workshop/01-setup.md) | Setup & Context Engineering |
| [**02**](workshop/02-design.md) | Design-First Frontend |
| [**03**](workshop/03-quiz-master.md) | Custom Quiz Master |
| [**04**](workshop/04-multi-agent.md) | Multi-Agent Development |

> 📝 Lab guides are also available in the [`workshop/`](workshop/) folder for offline reading.

---

## ✅ Build & test

```bash
cd socops
./mvnw clean package
```

```bash
cd socops
./mvnw test
```

---

## 📦 Deployment

Deploys automatically to GitHub Pages on push to `main`.

---

## 📣 Get involved

If you want to expand the game prompts, add a richer UI, or turn this into a remote-friendly social game, this project is a great starting point.
