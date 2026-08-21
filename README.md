# Sergey Kravtsov

Independent developer. Before that — ten years as CEO and CTO in Russian
manufacturing. I build and maintain the systems below; source code for client
projects is private.

Telegram [@gutugo](https://t.me/gutugo) · skravtsov@gmail.com ·
LinkedIn [serg-kravtsov](https://linkedin.com/in/serg-kravtsov)

---

## BigHouse CRM Agent

Analytical CRM for a larch and oak lumber manufacturer. Reads incoming email,
Telegram and phone calls, classifies each message with an LLM, maintains the
client and order database, and puts a morning report on the director's desk in
YouGile. Calls are transcribed locally and go through the same pipeline as text.

Python, FastAPI, SQLAlchemy async, PostgreSQL, Redis with arq, Qwen-Plus with a
local Ollama fallback, faster-whisper, React and Vite. Docker Compose on a
Mac Mini.

In production since March 2026, developed weekly.

## bighouse.ru

Product catalog for the same manufacturer. Not a store: visitors browse
products and send quote requests, which arrive in the CRM agent above.

Next.js, React, TypeScript, Prisma, PostgreSQL. PM2 and nginx on a VPS.

Live, developed weekly.

## Тропы — [tropy.app](https://tropy.app)

Hiking app for Russia's wild nature. Trail catalog with geometry taken from
OpenStreetMap, offline maps for places without a signal, GPS track recording,
and trail-condition reports left by people who walked there. My own product.

React Native and Expo, TypeScript, Fastify, PostgreSQL with PostGIS, MapLibre.
Three custom Android modules: RuStore push, power-saving detection, raw GNSS.

Backend in production on a Russian VPS. Android app pre-launch, going to
RuStore; builds will be published at [github.com/gutugo/tropy](https://github.com/gutugo/tropy).
[Article about the project on vc.ru](https://vc.ru/id5751611/2767681-alltrails-stoit-750-mln-v-rossii-net-analogov)

## Tion filter sales bot

B2B sales bot for a ventilation filter dealer: catalog, cart, checkout with
company lookup by INN, manager panel with editable orders, PDF invoices for two
legal entities, delivery by email and in chat.

Python, aiogram, SQLite, ReportLab, Dadata.

In production. Stable since May 2026 — nothing has needed changing.

---

## По-русски

Независимый разработчик. До этого — десять лет как CEO и CTO в производстве.
Веду системы ниже; исходники клиентских проектов приватные.

**BigHouse CRM Agent** — аналитическая CRM для производителя пиломатериалов из
лиственницы и дуба. Читает почту, Telegram и телефонные звонки, классифицирует
через LLM, ведёт базу клиентов и заказов, каждое утро приносит директору отчёт
в YouGile. Звонки расшифровываются локально и идут тем же конвейером, что и
текст. Python, FastAPI, PostgreSQL, Redis, Qwen-Plus с локальным Ollama
в резерве. В проде с марта 2026, дорабатывается каждую неделю.

**bighouse.ru** — каталог продукции того же производителя. Не магазин:
посетитель смотрит товары и отправляет запрос цены, запрос попадает в CRM-агента
выше. Next.js, Prisma, PostgreSQL. Живой, дорабатывается каждую неделю.

**Тропы ([tropy.app](https://tropy.app))** — приложение для пеших маршрутов по
дикой природе России. Каталог троп с геометрией из OpenStreetMap, офлайн-карты
для мест без связи, запись трека, отметки о состоянии тропы от тех, кто там
прошёл. Свой продукт. React Native, Fastify, PostgreSQL с PostGIS, MapLibre,
три своих Android-модуля. Бэкенд в проде, Android-приложение готовится
к публикации в RuStore, сборки будут выкладываться
в [github.com/gutugo/tropy](https://github.com/gutugo/tropy).
[Статья о проекте на vc.ru](https://vc.ru/id5751611/2767681-alltrails-stoit-750-mln-v-rossii-net-analogov)

**Бот продаж фильтров Tion** — B2B-бот для дилера фильтров вентиляции: каталог,
корзина, оформление с подтягиванием компании по ИНН, панель менеджера,
PDF-счета на два юрлица, отправка на почту и в чат. Python, aiogram, SQLite.
Работает в проде. С мая 2026 не менялся — не потребовалось.
