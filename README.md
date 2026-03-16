# Pedro — Full-Stack Developer & AI Engineer

Freelance developer focused on **AI integrations**, **automation**, and **API-driven backends**. Based in Brazil. Studying Computer Engineering.

I build things that talk to other things — WhatsApp bots, LLM pipelines, REST APIs, full-stack apps. If it involves Claude, OpenAI, n8n, or Evolution API, I'm probably already interested.

---

## Stack

**Languages** — Python, TypeScript, JavaScript, Node.js  
**Backends** — FastAPI, Express  
**AI/Automation** — Claude API, OpenAI API, Gemini API, n8n, Evolution API  
**Frontend** — React, Vite, Tailwind  
**Infra** — Docker, Docker Compose, SQLite, SQLAlchemy  
**Other** — WhatsApp integrations, JWT auth, web scraping, ML (scikit-learn)

---

## Projects

### MTG Stock Market
Full-stack Magic: The Gathering card price tracker — think Bloomberg Terminal, but for cardboard.

- **Backend**: FastAPI + SQLAlchemy + SQLite. REST API with JWT auth, freemium roles (free vs Pro), price history, news scraping, and ML-based price predictions using scikit-learn.
- **Frontend**: React + TypeScript + Vite. Dashboard with trending cards, portfolio tracker, price alerts, community comments, and an AI recommendations engine (Pro-only).
- **ML**: Linear regression model predicts 7-day price movements from historical data. Trending scores computed via scheduled daily jobs.
- **Infra**: Fully Dockerized (separate `Dockerfile` per service + `docker-compose`). PWA-ready with Workbox service worker.

Tech: `FastAPI` `SQLAlchemy` `scikit-learn` `React` `TypeScript` `Docker`

---

### MTG Deck Builder
AI-powered deck construction tool using Gemini 2.5 Pro as the backbone.

- Generates complete 60/100-card decklists from user-defined parameters (format, power level, playstyle, theme, colors, commander).
- Uses a **RAG loop**: Gemini calls a local `searchLocalDatabase` function tool to query a SQLite card database mid-generation, verifying legality and prices before finalizing the list.
- Supports deck **upgrade analysis**: paste an existing list, get 6–12 specific 1-for-1 swap recommendations with priority ratings.
- Full auth system (JWT), card hover tooltips, vault to save decks, upgrade sidebar with AI suggestions.
- Backend: Express + TypeScript + SQLite (local card DB seeded from Scryfall bulk data).
- Frontend: React + TypeScript + Vite + Gemini SDK.

Tech: `Gemini` `React` `TypeScript` `Express` `SQLite` `Docker`

---

### [Talent ADS](https://talentads.com.br)
CV analysis platform powered by Gemini. HR dashboard for comparing multiple CVs side-by-side, deployed via GitHub Pages.

---

## Other work

- **WhatsApp integrations** — bots and automation pipelines using Evolution API + n8n
- **API automation** — async Python scripts, brute-force testing, custom HTTP clients
- **LaTeX technical translation** — 44-page offshore equipment procedure spec (Baker Hughes / GranMorgu Project) from EN to PT-BR
- **AI image generation prompts** — for book cover design and illustration workflows

---

## Writing

Working on **A Colheita de Mentes — Ecos, Vol. 1**, a cyberpunk novel set in a dystopian city called Dicotomia. Preparing for self-publication via Amazon KDP.

---

## Contact

**Freelance (99Freelas)**: [IPedrax](https://www.99freelas.com.br/user/ipedrax)   
**Twitter/X**: [@ipedrax](https://twitter.com/ipedrax)
