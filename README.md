<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=timeGradient&customColorList=0,2,4,8,30&height=200&section=header&text=rxritet&fontSize=80&fontAlignY=35&animation=twinkling&fontColor=fff" />
</p>

<div align="center">

<h1>Привет, я Радмир!</h1>

### Backend/Go Developer · Full-Stack · Almaty, KZ

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/radmir-abraev-186b393b0/) [![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:abraevradmir2@gmail.com) [![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/rxritet)

</div>

---

## О себе

Студент 2-го курса Software Engineering. Моя цель — стать сильным Backend-разработчиком с основным фокусом на **Go** и пониманием всего цикла разработки (Full-Stack). Пишу чистый код, ценю конкретику, измеримые результаты и системный подход к задачам.

Сейчас активно работаю над собственными проектами, расширяю стек технологий и открыт к первым коммерческим ролям.

---

> [!IMPORTANT]
> <details>
> <summary><b>Ключевые компетенции</b></summary>
>
> <br>
>
> • <b>Backend-разработка на Go</b>: чистый net/http, Cobra CLI, Mage, работа с PostgreSQL и BoltDB, архитектурные паттерны (tx-in-context, domain/service/web)<br>
> • <b>Full-Stack на Flutter/Dart</b>: Clean Architecture, Riverpod, Dart Shelf, WebSocket real-time, JWT-аутентификация<br>
> • <b>Frontend-разрабка</b>: React 19, TypeScript, Tailwind CSS, TanStack Query, Zustand, Vite<br>
> • <b>Python Backend</b>: Django REST Framework, FastAPI, ORM, миграции<br>
> • <b>DevOps база</b>: Docker, nginx, systemd, rsync-деплой, GitHub Actions<br>
> • <b>UI/UX</b>: прототипирование в Figma, адаптивная вёрстка, Material 3<br>
>
> </details>

> [!IMPORTANT]
> <details>
> <summary><b>Текущий фокус</b></summary>
>
> <br>
>
> • <b>Specto</b> — production-готовое Go-приложение: дорабатываю деплой на VPS, настраиваю nginx + systemd<br>
> • <b>HabitDuel</b> — дорабатываю FCM push-уведомления и систему друзей<br>
> • <b>Go углубление</b>: продвинутые паттерны, обработка ошибок, тестирование (Testcontainers, фаззинг)<br>
> • <b>Open Source проекты</b>: изучаю хорошо оформленные Go-репозитории, чтобы улучшать практику чтения чужого кода<br>
> • <b>English B1 → B2</b>: целенаправленно прочитываю документацию и spec на английском<br>
>
> </details>

> [!NOTE]
> <details>
> <summary><b>Опыт & деятельность</b></summary>
>
> <br>
>
> #### **AlmaU — IT-отдел | Стажировка**
> Администрирование компьютерной сети ~200 пк, учёт оборудования по подразделениям, прокладка сети в ~100 кабинетах.
>
> #### **AlmaU — Отдел коммерциализации | Стажировка**
> Верификация проектов, поддержка Instagram-аккаунта отдела, разработка 12-страничного сайта для департамента.
>
> #### **Самостоятельные проекты**
> Specto (Go, production-ready), HabitDuel (Flutter + Dart Shelf, fullstack), SpoitHub (React + Django, SaaS).
>
> </details>

---

## Технологический стек

<table align="center" style="border: none;">
  <tr>
    <td align="right"><b>Языки программирования</b></td>
    <td><img src="https://skillicons.dev/icons?i=go,py,ts,js,dart" alt="Languages"/></td>
  </tr>
  <tr>
    <td align="right"><b>Backend & Базы данных</b></td>
    <td><img src="https://skillicons.dev/icons?i=django,fastapi,postgres,sqlite,node" alt="Backend"/></td>
  </tr>
  <tr>
    <td align="right"><b>Frontend & Мобильная разработка</b></td>
    <td><img src="https://skillicons.dev/icons?i=react,tailwind,vite,figma,flutter,html,css" alt="Frontend"/></td>
  </tr>
  <tr>
    <td align="right"><b>DevOps & Облако</b></td>
    <td><img src="https://skillicons.dev/icons?i=docker,aws,nginx,linux" alt="DevOps"/></td>
  </tr>
  <tr>
    <td align="right"><b>Инструменты</b></td>
    <td><img src="https://skillicons.dev/icons?i=git,github,vscode,postman" alt="Tools"/></td>
  </tr>
</table>

> *Дополнительно в работе применяю: BoltDB, OpenTelemetry (slog/otelslog), Testcontainers, Mage, Django REST Framework, Zustand, TanStack Query, React Hook Form, Zod.*

---

## Проекты

### [⚙️ Specto](https://github.com/rxritet/Specto)
**Производительное веб-приложение для управления задачами на Go.**
- **Стек:** Go 1.25, net/http (Go 1.22+ pattern matching), PostgreSQL, BoltDB, Cobra CLI, Mage, OpenTelemetry, Testcontainers.
- **Архитектура:** Монолит с чёткими слоями (domain / service / web), tx-in-context, UI Decorator-паттерн, go:embed assets.
- **Особенности:** SIMD AVX2-агрегация на amd64 с pure-Go fallback; двойная стратегия БД (BoltDB dev / PostgreSQL prod); автодеплой через Mage → rsync → systemd.

### [⚔️ HabitDuel](https://github.com/rxritet/HabitDuel)
**Fullstack Dart-приложение для соревновательного трекинга привычек.**
- **Стек:** Flutter 3, Riverpod 2.5, Dio, WebSocket — клиент; Dart Shelf, PostgreSQL, JWT — сервер.
- **Архитектура:** Clean Architecture на клиенте (domain / data / presentation); слоистый бэкенд (handlers / services / middleware / websocket / cron).
- **Функционал:** 1v1 дуэли, ежедневные check-in'ы с UTC-верификацией, real-time обновления через WebSocket, лидерборд, бейджи, локальные push-уведомления.

### [🏟️ SpoitHub](https://github.com/SpoitHub/delux)
**SaaS-платформа для спортивных мероприятий и маркетплейс экипировки.**
- **Стек:** React 19, TypeScript, Tailwind CSS, Django REST Framework, PostgreSQL, Docker.
- **Архитектура:** Decoupled SPA — чёткое разделение Frontend и Backend.
- **Функционал:** Ролевая модель, каталог событий, билеты с QR-кодами, магазин товаров, REST API.

### Образовательные репозитории
- **[GoLang Education](https://github.com/rxritet/GoLang-Education):** Горутины, каналы, паттерны, BoltDB и REST API на Go.
- **[FastAPI](https://github.com/rxritet/FastAPI-Education) & [Django Education](https://github.com/rxritet/Django-Education):** API, ORM, модели, аутентификация.
- **[Frontend & Mobile Education](https://github.com/rxritet/Frontend-Education):** TypeScript, React, адаптивная вёрстка.

---

## GitHub Статистика

<div align="center">

![GitHub Streak](https://streak-stats.demolab.com?user=rxritet&theme=dark&hide_border=true&background=0d1117&ring=ffffff&fire=ffffff&currStreakLabel=ffffff&sideLabels=8b949e&dates=8b949e&currStreakNum=ffffff&sideNums=ffffff)

<img height="160" src="https://github-readme-stats-theta-orcin-12.vercel.app/api?username=rxritet&show_icons=true&theme=dark&hide_border=true&count_private=true&bg_color=0d1117" />
<img height="160" src="https://github-readme-stats-theta-orcin-12.vercel.app/api/top-langs/?username=rxritet&layout=compact&theme=dark&hide_border=true&bg_color=0d1117" />

</div>

---

## Roadmap 2026

- [x] Старт с Go — основы языка, конкурентность
- [x] REST API на Go / Python (Django, FastAPI)
- [x] Первый full-stack проект с Go бэкендом — **Specto** ✅
- [x] Первое функциональное мобильное приложение — **HabitDuel** ✅
- [ ] Первый рабочий Figma прототип
- [ ] Деплой production-проекта на VPS (systemd + nginx)
- [ ] **Первая коммерческая роль разработчика 🚀**

---

<div align="center">

**Готов к тестовым заданиям, стажировкам и продуктивной работе**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/radmir-abraev-186b393b0/) [![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:abraevradmir2@gmail.com) [![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/rxritet)

</div>
