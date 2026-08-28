# gal1ce
> 16, Turkey. self-taught.
>
> backend and systems. i like the layer underneath the one everybody uses.

---

<img src="github-metrics.svg" />

---

## Things i've built

### [Indium](https://github.com/gal1ce/indium) — Narrative-First 2D Game Engine `C++20`
scene editor · hot-reload native scripting · dialogue / quest / cutscene systems · SAT collision · component-based scene graph · Linux / macOS / Windows

Scripts compile to shared libraries and reload at runtime, with the same toolchain the engine was built with. Properties reach the inspector through a single macro, no boilerplate.

### [Kintsugi](https://github.com/gal1ce/kintsugi) — Storage Engine + Credential Manager `C++20`
hand-written B+tree · paged binary disk format · buffer pool · write-ahead log · libsodium auth

No SQLite, no JSON, no third-party database. Page I/O, the tree, and crash recovery are all written from scratch, because ordered lookup and ordered listing are what a B+tree is good at — which is exactly what the program is for.

### [Yugen](https://github.com/gal1ce/yugen) — Desktop Music Player `C++23`
Saucer/WebKit · React/TS frontend · miniaudio · yt-dlp · Last.fm
Local library scanning, YouTube and SoundCloud search with download, lyrics, playlists, Discord Rich Presence, and a recommendation page powered by Last.fm. Ships as an AppImage.

### [EcoFil](https://github.com/gal1ce/ecofil) — Media Library & Discovery Platform `Python`
FastAPI (async) · PostgreSQL + SQLAlchemy + Alembic · JWT + Google OAuth · RBAC · rate limiting · async TTL cache · Docker

Aggregates TMDB, OMDb and AniList behind one provider interface with a merge layer, serves LLM-backed recommendations that explain themselves, and handles direct messaging with an inbox and message requests. Next.js 15 web client, Expo mobile client.

### [eco](https://github.com/gal1ce/eco) — Update Manager for Arch `Python`
pacman · AUR · flatpak · tracked git repos, in one command

Read-only checks run in parallel behind a live TUI, then you choose what to apply. Updates run one at a time with the real tool attached to your terminal, so prompts behave normally and the result you see is the one pacman actually reported.

### [ffpilot](https://github.com/gal1ce/ffpilot) — ffmpeg TUI `C++17`
trim · speed · compress, without memorizing flags · FTXUI · one-line installer

---

## Also

[Turkish news classifier](https://github.com/gal1ce/ttc4900) — BERT fine-tune on TTC4900, served over FastAPI. Some smaller ML experiments and a Discord bot live in private repos.

---

## Stack
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

---

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=gal1ce&theme=tokyo-night&hide_border=true" />
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/gal1ce/gal1ce/output/github-contribution-grid-snake-dark.svg" />
</p>
