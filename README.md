# Виталий Останин

[English version](./README-en.md)

**Senior Backend Developer / Tech Lead**
vitaly.ostanin@gmail.com | [GitHub](https://github.com/VitalyOstanin) | [Резюме (RU)](https://github.com/VitalyOstanin/resume/blob/master/README.md) | [Резюме (EN)](https://github.com/VitalyOstanin/resume/blob/master/README.en.md)

> **Примечание**: Живу и работаю в Санкт-Петербурге, Россия

## Обо мне

Backend-инженер и Tech Lead. **Более 25 лет в ИТ** и **более 13 лет на Node.js**.

Из недавнего:
- спроектировал 4-уровневую систему кэширования, давшую рост RPS в 50–100 раз на проблемных endpoints;
- реализовал интеграции с платёжными системами (CloudPayments, T-Bank, Robokassa) и amoCRM;
- вывел из эксплуатации 14 устаревших сервисов в пользу 4 новых с поддерживаемым стеком;
- в проекте под NDA спроектировал и реализовал финансовое ядро на PostgreSQL для приёма депозитов, начислений и выплат.

Фокус: production-надёжность, наблюдаемость, прагматичное внедрение AI-ассистентов в работу команд.

## Ключевые навыки

- **Backend-разработка**: Node.js, TypeScript, NestJS, JavaScript (основные); Python, Rust (с помощью AI-ассистентов)
- **Базы данных**: PostgreSQL (включая транзакционные финансовые сценарии), MongoDB
- **Кэширование и очереди**: Redis, RabbitMQ, Kafka, NATS, pg-boss
- **Системная архитектура**: микросервисы, проектирование API, многоуровневое кэширование, распределённые системы
- **DevOps и инфраструктура**: Kubernetes (в т.ч. Yandex Cloud Managed Kubernetes), Docker, Podman, Buildah, Helm, GitLab CI/CD, Harbor
- **Linux**: более 20 лет опыта с серверными и десктопными окружениями
- **Тестирование**: unit (Vitest, Jest), integration, E2E (supertest), нагрузочное (k6); отладка утечек памяти в production
- **Инструменты разработчика**: MCP-серверы, ESLint-плагины, инструменты отладки

## Избранные проекты

<table align="center">
<tr>
  <td width="50%" align="center">
    <h3>MCP Chrome Debugger Protocol</h3>
    <p>🔧 Продвинутое решение для отладки Node.js приложений через Chrome DevTools Protocol</p>
    <p>
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
      <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white"/>
      <img src="https://img.shields.io/badge/Chrome_DevTools-4285F4?style=flat-square&logo=googlechrome&logoColor=white"/>
    </p>
    <a href="https://github.com/VitalyOstanin/mcp-chrome-debugger-protocol">Посмотреть проект →</a>
  </td>
  <td width="50%" align="center">
    <h3>YouTrack MCP Server</h3>
    <p>🎯 Полнофункциональная интеграция с YouTrack — управление задачами и продвинутая отчётность</p>
    <p>
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
      <img src="https://img.shields.io/badge/MCP-FF6B6B?style=flat-square&logo=&logoColor=white"/>
      <img src="https://img.shields.io/badge/YouTrack-000000?style=flat-square&logo=jetbrains&logoColor=white"/>
    </p>
    <a href="https://github.com/VitalyOstanin/youtrack-mcp">Посмотреть проект →</a>
  </td>
</tr>

<tr>
  <td width="50%" align="center">
    <h3>MongoDB MCP Server</h3>
    <p>🗄️ Полнофункциональная интеграция с MongoDB — безопасный режим и потоковый экспорт</p>
    <p>
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
      <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white"/>
      <img src="https://img.shields.io/badge/MCP-FF6B6B?style=flat-square&logo=&logoColor=white"/>
    </p>
    <a href="https://github.com/VitalyOstanin/mongodb-mcp">Посмотреть проект →</a>
  </td>
  <td width="50%" align="center">
    <h3>PostgreSQL MCP Server</h3>
    <p>🐘 Интеграция с PostgreSQL — операции с БД и анализ схем</p>
    <p>
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
      <img src="https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white"/>
      <img src="https://img.shields.io/badge/MCP-FF6B6B?style=flat-square&logo=&logoColor=white"/>
    </p>
    <a href="https://github.com/VitalyOstanin/postgres-mcp">Посмотреть проект →</a>
  </td>
</tr>
<tr>
  <td width="50%" align="center">
    <h3>Markdown Org Extract</h3>
    <p>📝 Инструмент на Rust для организации Markdown контента в стиле Org Mode</p>
    <p>
      <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white"/>
      <img src="https://img.shields.io/badge/Markdown-000000?style=flat-square&logo=markdown&logoColor=white"/>
      <img src="https://img.shields.io/badge/Org_Mode-77AA99?style=flat-square&logo=&logoColor=white"/>
    </p>
    <a href="https://github.com/VitalyOstanin/markdown-org-extract">Посмотреть проект →</a>
  </td>
  <td width="50%" align="center">
    <h3>ESLint Prefer De Morgan's Law</h3>
    <p>⚡ ESLint правило для применения закона Де Моргана и улучшения читаемости кода</p>
    <p>
      <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black"/>
      <img src="https://img.shields.io/badge/ESLint-4B32C3?style=flat-square&logo=eslint&logoColor=white"/>
      <img src="https://img.shields.io/badge/NPM-CB3837?style=flat-square&logo=npm&logoColor=white"/>
    </p>
    <a href="https://github.com/VitalyOstanin/eslint-prefer-de-morgan-law">Посмотреть проект →</a>
  </td>
</tr>
<tr>
  <td width="50%" align="center">
    <h3>Telegram Exporter</h3>
    <p><img src="https://cdn.simpleicons.org/telegram/26A5E4" width="16" height="16" alt="Telegram"/> Экспорт чатов и медиа Telegram на локальный диск с гибкой настройкой</p>
    <p>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
      <img src="https://img.shields.io/badge/Telegram-26A5E4?style=flat-square&logo=telegram&logoColor=white"/>
      <img src="https://img.shields.io/badge/Jinja-B41717?style=flat-square&logo=jinja&logoColor=white"/>
    </p>
    <a href="https://github.com/VitalyOstanin/tg-export">Посмотреть проект →</a>
  </td>
  <td width="50%" align="center"></td>
</tr>
</table>

## Избранные достижения

- **Производительность**: рост RPS в 50–100 раз на проблемных endpoints за счёт 4-уровневой системы кэширования (кэш in-flight Promise → in-memory LRU/TTL → Redis → БД)
- **Финансовое ядро (проект под NDA)**: спроектировал и реализовал предметную область на PostgreSQL для приёма депозитов, начислений и выплат
- **Интеграции**: CloudPayments (платежи + чеки 54-ФЗ), T-Bank, Robokassa, amoCRM
- **Сокращение legacy**: вывел из эксплуатации 14 сервисов с неподдерживаемым кодом, заменив на 4 сервиса с поддерживаемым стеком
- **Инфраструктура**: развернул ~30 унаследованных Node.js-микросервисов в Yandex Cloud Managed Kubernetes; создал безопасный и быстрый GitLab Runner (unprivileged Podman + Buildah + Harbor); настроил пайплайны build + deploy в Kubernetes
- **Оптимизация затрат**: вывел нагрузку из DigitalOcean и Hetzner; подготовил план отказа от Cloudflare
- **AI в работе команды**: внедрил AI-ассистентов (Claude Code, OpenAI Codex, VS Code Cline) в ежедневный рабочий процесс; обучил backend- и frontend-разработчиков работе с Kubernetes и отладке Node.js в нём
- **Найм**: участвовал в закрытии позиций backend и DevOps

## Текущий фокус

- **MCP-серверы**: специализированные серверы для работы с Anthropic Claude, OpenAI, Qwen, DeepSeek
- **AI в production-разработке**: прагматичное внедрение AI-ассистентов в backend-разработку, тестирование и эксплуатацию
- **Developer Experience**: инструменты и процессы для современных команд

## Языки программирования и технологии

**Программирование (основные)**: TypeScript, JavaScript, Node.js, NestJS  
**Программирование (с помощью AI-ассистентов)**: Python, Rust  
**Базы данных**: PostgreSQL, MongoDB  
**Кэширование и очереди**: Redis, RabbitMQ, Kafka, NATS, pg-boss  
**Инфраструктура**: Kubernetes, Yandex Cloud, Docker, Podman, Buildah, Helm, GitLab CI/CD, Harbor, Linux  
**Тестирование**: unit (Vitest, Jest), integration, E2E (supertest), нагрузочное (k6)  
**Инструменты**: Git, ESLint, Webpack, Vite

---

*Открыт для сотрудничества в проектах, связанных с инструментами разработчика и интеграцией AI.*
