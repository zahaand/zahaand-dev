🇷🇺 Описание на русском ниже / 🇬🇧 Russian description below

---

# zahaand.dev — Portfolio Website

Personal portfolio website of Andrei Zakharenkov, Java Backend Developer available for freelance.

![HTML](https://img.shields.io/badge/HTML5-single_file-orange?style=flat-square&logo=html5)
![CSS](https://img.shields.io/badge/CSS3-vanilla-blue?style=flat-square&logo=css3)
![JavaScript](https://img.shields.io/badge/JavaScript-vanilla-yellow?style=flat-square&logo=javascript)
![Deployed on Vercel](https://img.shields.io/badge/Deployed-Vercel-black?style=flat-square&logo=vercel)
![SEO](https://img.shields.io/badge/SEO-optimized-green?style=flat-square)
![Analytics](https://img.shields.io/badge/Analytics-Yandex.Metrika-red?style=flat-square)

## About

Static portfolio website built as a single self-contained `index.html` file — no frameworks, no build step, no external dependencies. All assets (photo, screenshots) are Base64-embedded. Includes a separate `privacy.html` for the privacy policy.

**Live:** [zahaand.dev](https://zahaand.dev)

## Features

- 🌙 / ☀️ Dark / light theme toggle
- 🇷🇺 / 🇬🇧 RU / EN language switch — full content translation, preference saved in `localStorage`
- 💻 Interactive terminal with 9 commands — fully bilingual (RU/EN)
- 🐛 Hidden game — catch bugs before they reach production (`play` in terminal)
- 🎮 Konami code easter egg (↑↑↓↓←→←→BA)
- 🔍 SEO-optimized: meta tags, Open Graph, Twitter Card, Schema.org JSON-LD
- 📱 Fully responsive — mobile (375px), tablet, desktop
- 📊 Yandex.Metrika analytics (non-blocking, `defer`)
- 🍪 Cookie consent banner with link to privacy policy
- 🔒 Privacy policy page (`privacy.html`)

## Terminal Commands

| Command | Description (RU/EN) |
|---------|---------------------|
| `help` | List all available commands |
| `whoami` | About me |
| `skills` | Full tech stack |
| `projects` | Portfolio projects with GitHub links |
| `services` | What I can build for you |
| `contact` | Phone, Telegram, Email, GitHub |
| `fact` | Random fact from my projects (bilingual) |
| `play` | 🐛 Hidden game: catch bugs before prod |
| `clear` | Clear the terminal |

**DevTools easter egg:** open browser console and run `hire()`.

## Portfolio Projects

| Project | Stack | Status |
|---------|-------|--------|
| [LifeSync Backend](https://github.com/zahaand/lifesync-backend) | Java 21, Spring Boot 3.5, Kafka, jOOQ, PostgreSQL | ✅ v1.0.0 |
| [LifeSync Frontend](https://github.com/zahaand/lifesync-frontend) | React 18, TypeScript, Vite, Tailwind v4, shadcn/ui | ✅ v1.0.0 |
| [smart-task-bot](https://github.com/zahaand/smart-task-bot) | Java 21, Spring Boot, Telegram Bot API, PostgreSQL | ✅ v1.0.0 |

## Technology Stack (Website)

| Concern | Technology |
|---------|------------|
| Markup | HTML5 (semantic) |
| Styling | CSS3 with CSS variables (dark/light themes) |
| Logic | Vanilla JavaScript (ES6+) |
| Fonts | JetBrains Mono, Fira Code, Cascadia Code |
| Images | Base64-embedded JPEG |
| Analytics | Yandex.Metrika (counter 108510324, non-blocking) |
| Deployment | Vercel (auto-deploy from GitHub) |
| SEO | Schema.org JSON-LD, Open Graph, Twitter Card |

## File Structure

```
zahaand-dev/
├── index.html                      # Main portfolio page (single file, ~310KB)
├── privacy.html                    # Privacy policy page
└── yandex_4fc6ae58d6e69182.html   # Yandex Webmaster verification
```

## Architecture

```
index.html
├── <head>
│   ├── Yandex.Metrika (defer, non-blocking)
│   ├── SEO meta tags, Open Graph, Schema.org JSON-LD
│   └── CSS (dark/light themes via CSS variables)
├── <body>
│   ├── <nav>        — sticky nav, theme toggle, lang toggle
│   ├── #about       — hero, JSON card, badges, photo
│   ├── #skills      — 9 skill cards (01)
│   ├── #projects    — 2 project cards with screenshots (02)
│   ├── #bots        — horizontal bot card with phone frame (03)
│   ├── #services    — 4 service cards with contact dropdown (04)
│   ├── #rec         — recommendation letter (05)
│   ├── #terminal    — interactive bilingual terminal (06)
│   ├── #contact     — contact bar: Call, Telegram, Email, GitHub
│   ├── <footer>
│   └── cookie-banner — consent banner with privacy policy link
└── <script>
    ├── setTheme()        — dark/light toggle
    ├── setLang()         — RU/EN switch, saves to localStorage
    ├── CMDS{}            — bilingual terminal command handlers
    ├── gameLoop()        — bug catcher game (Canvas 2D)
    ├── toggleDrop()      — service card contact dropdown
    ├── acceptCookies()   — cookie consent
    ├── showKonami()      — easter egg overlay
    └── hire()            — DevTools contact card
```

## SEO

```html
<meta name="description" content="Java Backend разработчик, 5 лет опыта..."/>
<meta name="keywords" content="Java разработчик, Spring Boot developer, backend freelance..."/>
<link rel="canonical" href="https://zahaand.dev/"/>
<meta property="og:type" content="website"/>
<meta property="og:title" content="Andrei Zakharenkov — Java Backend Developer"/>
<script type="application/ld+json">
{ "@type": "Person", "name": "Andrei Zakharenkov", ... }
</script>
```

Indexed in:
- [Google Search Console](https://search.google.com/search-console)
- [Yandex Webmaster](https://webmaster.yandex.ru)

## Services

- **Backend service** — Java 21, Spring Boot, Kafka, PostgreSQL, JWT, Swagger
- **Fullstack web application** — React + TypeScript + Java + Spring Boot
- **Telegram bot** — any complexity, multilingual, Railway deployment
- **Website development** — landing page, business card, corporate site, SEO

## Contact

- 📞 [+7 (921) 580-07-06](tel:+79215800706)
- 💬 Telegram: [@zahaand](https://t.me/zahaand)
- 📧 Email: [zahaand@gmail.com](mailto:zahaand@gmail.com)
- 🐙 GitHub: [github.com/zahaand](https://github.com/zahaand)

## Related Projects

- [LifeSync Backend](https://github.com/zahaand/lifesync-backend) — Java 21, Spring Boot 3.5, PostgreSQL 16, Apache Kafka
- [LifeSync Frontend](https://github.com/zahaand/lifesync-frontend) — React 18, TypeScript 5, Vite, Tailwind CSS v4
- [smart-task-bot](https://github.com/zahaand/smart-task-bot) — Java 21, Spring Boot, Telegram Bot API, 382 tests

---

# zahaand.dev — Сайт-портфолио

Персональный сайт-портфолио Захаренкова Андрея, Java Backend разработчика, открытого для фриланс-проектов.

## О сайте

Статический сайт-портфолио в виде единого самодостаточного файла `index.html` — без фреймворков, без сборки, без внешних зависимостей. Все ресурсы (фото, скриншоты) встроены как Base64. Отдельная страница `privacy.html` — политика конфиденциальности.

**Сайт:** [zahaand.dev](https://zahaand.dev)

## Возможности

- 🌙 / ☀️ Переключение тёмной/светлой темы
- 🇷🇺 / 🇬🇧 Переключение языков RU / EN — полный перевод контента, выбор сохраняется в `localStorage`
- 💻 Интерактивный терминал с 9 командами — полностью двуязычный (RU/EN)
- 🐛 Скрытая игра — лови баги до того как они уйдут в прод (команда `play` в терминале)
- 🎮 Пасхалка Konami code (↑↑↓↓←→←→BA)
- 🔍 SEO-оптимизация: meta-теги, Open Graph, Twitter Card, Schema.org JSON-LD
- 📱 Полная адаптация — мобильные (375px), планшет, десктоп
- 📊 Яндекс.Метрика (неблокирующая загрузка, `defer`)
- 🍪 Cookie-баннер с согласием и ссылкой на политику конфиденциальности
- 🔒 Страница политики конфиденциальности (`privacy.html`)

## Команды терминала

| Команда | Описание |
|---------|----------|
| `help` | Список всех команд |
| `whoami` | Обо мне |
| `skills` | Полный стек технологий |
| `projects` | Проекты портфолио со ссылками на GitHub |
| `services` | Что могу сделать для вас |
| `contact` | Телефон, Telegram, Email, GitHub |
| `fact` | Случайный факт из моих проектов (двуязычный) |
| `play` | 🐛 Скрытая игра: лови баги до прода |
| `clear` | Очистить терминал |

**Пасхалка в DevTools:** откройте консоль браузера и выполните `hire()`.

## Проекты в портфолио

| Проект | Стек | Статус |
|--------|------|--------|
| [LifeSync Backend](https://github.com/zahaand/lifesync-backend) | Java 21, Spring Boot 3.5, Kafka, jOOQ, PostgreSQL | ✅ v1.0.0 |
| [LifeSync Frontend](https://github.com/zahaand/lifesync-frontend) | React 18, TypeScript, Vite, Tailwind v4, shadcn/ui | ✅ v1.0.0 |
| [smart-task-bot](https://github.com/zahaand/smart-task-bot) | Java 21, Spring Boot, Telegram Bot API, PostgreSQL | ✅ v1.0.0 |

## Стек технологий (сайт)

| Область | Технология |
|---------|------------|
| Разметка | HTML5 (семантический) |
| Стили | CSS3 с CSS-переменными (тёмная/светлая тема) |
| Логика | Vanilla JavaScript (ES6+) |
| Шрифты | JetBrains Mono, Fira Code, Cascadia Code |
| Изображения | Base64-встроенные JPEG |
| Аналитика | Яндекс.Метрика (счётчик 108510324, неблокирующая) |
| Деплой | Vercel (автодеплой из GitHub) |
| SEO | Schema.org JSON-LD, Open Graph, Twitter Card |

## Структура файлов

```
zahaand-dev/
├── index.html                      # Основная страница портфолио (~310 KB)
├── privacy.html                    # Политика конфиденциальности
└── yandex_4fc6ae58d6e69182.html   # Верификация Яндекс Вебмастер
```

## Архитектура

```
index.html
├── <head>
│   ├── Яндекс.Метрика (defer, неблокирующая)
│   ├── SEO meta-теги, Open Graph, Schema.org JSON-LD
│   └── CSS (тёмная/светлая тема через CSS-переменные)
├── <body>
│   ├── <nav>        — sticky навбар, переключатель темы и языка
│   ├── #about       — hero, JSON-карточка, бейджи, фото
│   ├── #skills      — 9 карточек навыков (01)
│   ├── #projects    — 2 карточки проектов со скриншотами (02)
│   ├── #bots        — горизонтальная карточка бота с рамкой телефона (03)
│   ├── #services    — 4 карточки услуг с dropdown-меню связи (04)
│   ├── #rec         — рекомендательное письмо (05)
│   ├── #terminal    — двуязычный интерактивный терминал (06)
│   ├── #contact     — панель: Позвонить, Telegram, Email, GitHub
│   ├── <footer>
│   └── cookie-banner — баннер согласия со ссылкой на политику
└── <script>
    ├── setTheme()        — переключение темы
    ├── setLang()         — переключение RU/EN, сохранение в localStorage
    ├── CMDS{}            — двуязычные обработчики команд терминала
    ├── gameLoop()        — игра "лови баги" (Canvas 2D)
    ├── toggleDrop()      — dropdown-меню кнопок услуг
    ├── acceptCookies()   — принятие cookie
    ├── showKonami()      — пасхалка Konami
    └── hire()            — карточка контактов в DevTools
```

## SEO

```html
<meta name="description" content="Java Backend разработчик, 5 лет опыта..."/>
<meta name="keywords" content="Java разработчик, Spring Boot developer, backend freelance..."/>
<link rel="canonical" href="https://zahaand.dev/"/>
<meta property="og:type" content="website"/>
<meta property="og:title" content="Andrei Zakharenkov — Java Backend Developer"/>
<script type="application/ld+json">
{ "@type": "Person", "name": "Andrei Zakharenkov", ... }
</script>
```

Индексация:
- [Google Search Console](https://search.google.com/search-console)
- [Яндекс Вебмастер](https://webmaster.yandex.ru)

## Услуги

- **Backend-сервис** — Java 21, Spring Boot, Kafka, PostgreSQL, JWT, Swagger
- **Fullstack веб-приложение** — React + TypeScript + Java + Spring Boot
- **Telegram-бот** — любой сложности, многоязычный, деплой на Railway
- **Создание сайта** — лендинг, визитка, корпоративный сайт, SEO

## Контакты

- 📞 [+7 (921) 580-07-06](tel:+79215800706)
- 💬 Telegram: [@zahaand](https://t.me/zahaand)
- 📧 Email: [zahaand@gmail.com](mailto:zahaand@gmail.com)
- 🐙 GitHub: [github.com/zahaand](https://github.com/zahaand)

## Связанные проекты

- [LifeSync Backend](https://github.com/zahaand/lifesync-backend) — Java 21, Spring Boot 3.5, PostgreSQL 16, Apache Kafka
- [LifeSync Frontend](https://github.com/zahaand/lifesync-frontend) — React 18, TypeScript 5, Vite, Tailwind CSS v4
- [smart-task-bot](https://github.com/zahaand/smart-task-bot) — Java 21, Spring Boot, Telegram Bot API, 382 теста
