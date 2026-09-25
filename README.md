<div align="center">

# Bondarev Evgeni

**.NET-разработчик · AI-инструменты · автоматизация бизнес-процессов**

Проектирую и запускаю продакшн-системы, интеграции и LLM-сервисы,
а ещё небольшие продукты, которые решают одну задачу хорошо.

[![Telegram](https://img.shields.io/badge/Telegram-@Burn1ngSnow-2CA5E0?style=flat-square&logo=telegram&logoColor=white)](https://t.me/Burn1ngSnow)
[![TaskExtraction](https://img.shields.io/badge/task--extraction.ru-222?style=flat-square&logo=googlechrome&logoColor=white)](https://task-extraction.ru)
[![Docker Hub](https://img.shields.io/badge/Docker%20Hub-bondarevevgeni-2496ED?style=flat-square&logo=docker&logoColor=white)](https://hub.docker.com/u/bondarevevgeni)

</div>

---

## Сейчас

- **Studio2** — корпоративная PIM/WMS-система, в продакшне и ежедневной работе команды:
  - полный жизненный цикл заказа — от поставщика до клиента, возвраты и перемещения;
  - склады и синхронизация остатков с внешними системами;
  - интеграции с десятками поставщиков, CRM и учётными системами;
  - конвейеры фоновых задач с расписаниями, ретраями и логированием каждого шага;
  - row-level security: доступ к данным по организации, складу и статусу;
  - realtime-обновления интерфейса.

  .NET 8 · ASP.NET Core MVC · MySQL · Redis · Hangfire · SignalR · Docker. Покрытие тестами публикуется автоматически → [coverage-report](https://evgenibondarev.github.io/coverage-report/report/)
- **AI-first разработка** — Claude Code, собственные skills для ревью, тестов и разбора issues
- **Computer vision** — распознавание объектов по фото через vision-модели (в разработке)

## Проекты

### AI и продукты

| Проект | Что делает | Стек |
|---|---|---|
| **[TaskExtraction](https://github.com/EvgeniBondarev/TaskExtraction)** | Задачи из Telegram-чатов → LLM-классификация → канбан → Jira, Trello, GitHub Issues, Slack. [Сайт](https://task-extraction.ru) | FastAPI, Telethon, TypeScript, Docker |
| **[elicit-first](https://github.com/EvgeniBondarev/elicit-first)** | Системный промпт-скилл: заставляет AI-ассистента уточнить задачу до написания кода | Prompt engineering, Claude, GPT |

### Браузерные расширения

| Проект | Что делает | Стек |
|---|---|---|
| **[NetBorder](https://github.com/EvgeniBondarev/NetBorder)** | Показывает, когда вы на зарубежном сайте, считает внешний трафик и предупреждает о лимите | TypeScript, Manifest V3 |
| **[currency-converter-extension](https://github.com/EvgeniBondarev/currency-converter-extension)** | Находит цены на странице и показывает их в нужной валюте. Всё локально | JavaScript, Chrome |

### Backend

| Проект | Что делает | Стек |
|---|---|---|
| **[StudioB2B](https://github.com/EvgeniBondarev/StudioB2B)** | Multi-tenant SaaS: отдельная БД на каждого клиента, фоновые задачи, realtime | .NET 10, Blazor Server, MySQL, Hangfire |
| **[TecDocApi](https://github.com/EvgeniBondarev/TecDocApi)** | Web API большого каталога с быстрым полнотекстовым поиском | ASP.NET Core, Elasticsearch |
| **[PrApi](https://github.com/EvgeniBondarev/PrApi)** | Нечёткий поиск по каталогу, карточки, справочники, кэширование | .NET 8 Minimal API, EF Core, MySQL |
| **[telegram-forwarder](https://github.com/EvgeniBondarev/telegram-forwarder)** | Асинхронный микросервис очередей и отправки сообщений в Telegram | Python, FastAPI |
| **[Studio1-Web-Client](https://github.com/EvgeniBondarev/Studio1-Web-Client)** | Master-detail CRUD-клиент для OData API каталога | React, Ant Design, OData |

## Стек

<div align="center">

![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET%208-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![EF Core](https://img.shields.io/badge/EF%20Core-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
<br>
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white)
![Hangfire](https://img.shields.io/badge/Hangfire-2E3440?style=flat-square)
![SignalR](https://img.shields.io/badge/SignalR-512BD4?style=flat-square&logo=dotnet&logoColor=white)
<br>
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Claude](https://img.shields.io/badge/Claude%20Code-D97757?style=flat-square&logo=anthropic&logoColor=white)
![OpenRouter](https://img.shields.io/badge/OpenRouter-6566F1?style=flat-square)

</div>

## Активность

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/EvgeniBondarev/EvgeniBondarev/master/profile-3d-contrib/profile-night-green.svg">
  <img alt="3D contribution graph" src="https://raw.githubusercontent.com/EvgeniBondarev/EvgeniBondarev/master/profile-3d-contrib/profile-green.svg">
</picture>

</div>

---

<div align="center">

Открыт к сотрудничеству и интересным задачам — пишите в [Telegram](https://t.me/Burn1ngSnow).

</div>
