---
name: workspace
description: Repository-specific guidance for working in the Teste workspace.
---

- [ ] lint: `cd socops && ./mvnw test -DskipITs`
- [ ] build: `cd socops && ./mvnw clean package`
- [ ] test: `cd socops && ./mvnw test`

This repo has a Spring Boot web app in `socops` and workshop docs under `workshop/`.

Guidelines:
- Code lives in `socops`; keep changes small and game-focused.
- Backend: Spring Boot 3.4.2, Java 21.
- Frontend: Thymeleaf templates + `static/css/app.css` utilities.
- Use the existing CSS utility style; avoid adding large UI frameworks.
- Keep bilingual docs intact when editing workshop content.
- Use the Maven wrapper for runtime tasks: `./mvnw spring-boot:run`, `./mvnw clean package`, `./mvnw test`.

If UI work is involved, apply `frontend-design` guidance too.