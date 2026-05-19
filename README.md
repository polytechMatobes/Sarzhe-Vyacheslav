# CV Lab Starter

Стартер для лабораторной работы: персональный CV → CI/CD → GitHub Pages.

> During my school years, I was a <strong>two-time winner</strong> of the St. Petersburg stage of the All-Russian School Olympiad in Technology. I also participated in the Polytechnic University's summer school in <strong>"Data Analysis in Economics"</strong> and a specialized session at the All-Russian Children's Center "OKEAN." After gaining this experience, I realized I wanted to pursue a career in <strong>AI and fintech</strong>. So, I enrolled in the <strong>"Mathematical Support and Administration of Information Systems"</strong> program at SPbPU, and joined the SPbPU Student Scientific Society — AI track.

 About
During my school years, I was a two-time winner of the St. Petersburg stage of the All-Russian School Olympiad in Technology. I also participated in the Polytechnic University's summer school in "Data Analysis in Economics" and a specialized session at the All-Russian Children's Center "OKEAN." After gaining this experience, I realized I wanted to pursue a career in AI and fintech. So, I enrolled in the "Mathematical Support and Administration of Information Systems" program at SPbPU, and joined the SPbPU Student Scientific Society — AI track.
Projects
Battery Detector with ESP32-S3
2024 — 2025

Designed and manufactured a plexiglass sorting mechanism using Object Detection on an ESP32-S3 board with a camera module, stepper motor, servo drive, and IR sensor. Classifies batteries vs. non-batteries in real time.

Tic-Tac-Toe AI on 20×20 Grid (5 in a row)
Spring 2026

C++ implementation of Minimax with α-β pruning and a pattern evaluation table for 5-in-a-row combinations. Includes a full game interface and benchmarks against library algorithms.
Skills: C / C++; Python; Git; CI / CD; Linux; Object Detection; Minimax / α-β

## Стек

- [Vite](https://vitejs.dev/) — dev server + бандлер
- Vanilla JS + HTML + CSS (можешь добавить TS / фреймворк — на свой страх и риск, CI/lint придётся подкрутить)
- ESLint 9 (flat config) — линтер
- GitHub Actions — CI + CD

## Локальный запуск

```bash
npm install
npm run dev      # dev server на http://localhost:5173
npm run lint     # проверить код
npm run build    # собрать в dist/
npm run preview  # посмотреть прод-сборку локально
```

## Структура

```
.
├── .github/workflows/
│   ├── ci.yml        # PR → lint + build
│   └── deploy.yml    # main → GitHub Pages
├── src/
│   └── main.js       # JS-точка входа
├── index.html        # CV здесь
├── style.css
├── eslint.config.js
├── vite.config.js
└── package.json
```

## Что делать

1. Форкни template или используй "Use this template".
2. Сделай репо публичным.
3. **Settings → Pages → Source: GitHub Actions** (важно, без этого деплой не пройдёт).
4. Заведи ветку `feature/my-cv`, перепиши `index.html` / `style.css` под свой CV.
5. Открой PR в `main`. Дождись зелёного CI.
6. Merge. Смотри Actions — должен запуститься deploy.
7. Открой `https://<username>.github.io/<repo>/` — твой CV в проде.

Подробнее — `STUDENT_GUIDE.md`.

## Vibe coding log

- **LLM-ассистент:** Claude
- **2–3 ключевых промпта:**
  1. *Привет! Я пишу сайт-визитку и хочу сделать в ней что-то нестандартное и красивое. Может добавить анимации и красивый фон или есть другие прикольные фичи?* **Это был единственный промт**
- **Что правил(а) руками после генерации:** Ничего, всё классно работает

## Live URL

> https://polytechmatobes.github.io/Sarzhe-Vyacheslav/
