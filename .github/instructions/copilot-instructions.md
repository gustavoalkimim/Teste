---
name: copilot
description: Instructions for Copilot behavior and design guidance in this repository.
---

Design guide:
- Read the request carefully and keep changes small, focused, and context-aware.
- Prefer working within the existing `socops` Spring Boot app and the current Thymeleaf + CSS utility approach.
- For UI or page design, apply `frontend-design` guidance as a default.
- Use CSS variables, thoughtful typography, and layout harmony rather than adding new UI frameworks.
- Match the visual style to the repo's existing web app: clear game-focused UI, bold accents, and concise interaction patterns.
- Avoid generic or AI-style design; choose distinctive yet appropriate aesthetics that feel tailored to the app.

Implementation guidance:
- Use the repository's CSS utilities in `static/css/app.css` wherever possible.
- Keep bilingual and workshop docs changes consistent and preserve existing structure.
- When adding features, ensure backend and frontend remain aligned with the app's simple game flow.
- Prefer small CSS/HTML refinements over large rewrites.
