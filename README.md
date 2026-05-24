# Виталий Останин

[English version](./README-en.md)

**Senior Backend Developer / Tech Lead**
vitaly.ostanin@gmail.com | [GitHub](https://github.com/VitalyOstanin) | [Резюме (RU)](https://github.com/VitalyOstanin/resume/blob/master/README.md) | [Резюме (EN)](https://github.com/VitalyOstanin/resume/blob/master/README.en.md)

> **Примечание**: Живу и работаю в Санкт-Петербурге, Россия

## Обо мне

Backend-инженер и Tech Lead. **Более 25 лет в ИТ** и **более 13 лет на Node.js**.

Из недавнего:
- спроектировал 4-уровневую систему кэширования, давшую рост RPS в 50–100 раз на проблемных endpoints;
- восстановил неработавший приём платежей и формирование чеков (CloudPayments); подключил пул новых внешних систем — T-Bank, Robokassa, Yandex SmartCaptcha, amoCRM;
- вывел из эксплуатации 14 устаревших сервисов в пользу 4 новых с поддерживаемым стеком;
- в проекте под NDA спроектировал и реализовал финансовое ядро на PostgreSQL для приёма депозитов, начислений и выплат.

Удерживаю контекст крупных проектов на длительной перспективе; ориентируюсь в предметной области бизнеса (финтех, платежи, фискализация по 54-ФЗ, CRM-воронки, антифрод); беру на себя сложные и запущенные задачи.

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
    <h3>Sentry MCP Server</h3>
    <p>🐞 Интеграция с Sentry — список организаций и проектов, запросы issues с фильтрами и пагинацией</p>
    <p>
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
      <img src="https://img.shields.io/badge/Sentry-362D59?style=flat-square&logo=sentry&logoColor=white"/>
      <img src="https://img.shields.io/badge/MCP-FF6B6B?style=flat-square&logo=&logoColor=white"/>
    </p>
    <a href="https://github.com/VitalyOstanin/sentry-mcp">Посмотреть проект →</a>
  </td>
  <td width="50%" align="center">
    <h3>GitLab MCP Server</h3>
    <p>🦊 Интеграция с GitLab — проекты, merge requests с diff и поиском, теги SemVer next-release</p>
    <p>
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
      <img src="https://img.shields.io/badge/GitLab-FC6D26?style=flat-square&logo=gitlab&logoColor=white"/>
      <img src="https://img.shields.io/badge/MCP-FF6B6B?style=flat-square&logo=&logoColor=white"/>
    </p>
    <a href="https://github.com/VitalyOstanin/gitlab-mcp">Посмотреть проект →</a>
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
    <h3>Markdown Org для VS Code</h3>
    <p>🧩 Расширение VS Code для управления задачами в стиле Org Mode в Markdown-файлах</p>
    <p>
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
      <img src="https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white"/>
      <img src="https://img.shields.io/badge/Markdown-000000?style=flat-square&logo=markdown&logoColor=white"/>
    </p>
    <a href="https://github.com/VitalyOstanin/markdown-org-vscode">Посмотреть проект →</a>
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
  <td width="50%" align="center">
    <h3>Claude Dir Settings</h3>
    <p>🔀 Настройки Claude Code, привязанные к каталогу: <code>.claude-dir-settings.yaml</code> ищется вверх по дереву каталогов</p>
    <p>
      <img src="https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white"/>
      <img src="https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=anthropic&logoColor=white"/>
    </p>
    <a href="https://github.com/VitalyOstanin/claude-dir-settings">Посмотреть проект →</a>
  </td>
</tr>
</table>

## Избранные достижения

- **Производительность**: рост RPS в 50–100 раз на проблемных endpoints за счёт 4-уровневой системы кэширования (кэш in-flight Promise → in-memory LRU/TTL → Redis → БД)
- **Финансовое ядро (проект под NDA)**: спроектировал и реализовал предметную область на PostgreSQL для приёма депозитов, начислений и выплат
- **Интеграции (платежи + антифрод + CRM)**: восстановил CloudPayments (платежи и условное формирование чеков по 54-ФЗ); подключил пул новых внешних систем — T-Bank, Robokassa, Yandex SmartCaptcha, amoCRM
- **Сокращение legacy**: вывел из эксплуатации 14 сервисов с неподдерживаемым кодом, заменив на 4 сервиса с поддерживаемым стеком
- **Инфраструктура**: развернул ~30 унаследованных Node.js-микросервисов в Yandex Cloud Managed Kubernetes; создал безопасный и быстрый GitLab Runner (unprivileged Podman + Buildah + Harbor); настроил пайплайны build + deploy в Kubernetes
- **Оптимизация затрат**: вывел нагрузку из DigitalOcean и Hetzner; подготовил план отказа от Cloudflare
- **AI в работе команды**: внедрил AI-ассистентов (Claude Code, OpenAI Codex, VS Code Cline) в ежедневный рабочий процесс; обучил backend- и frontend-разработчиков работе с Kubernetes и отладке Node.js в нём
- **Найм**: участвовал в закрытии позиций backend и DevOps
- **Контекст и домен**: удерживаю контекст крупных проектов на длительной перспективе; ориентируюсь в предметной области финтеха (платежи, фискализация, CRM-воронки, антифрод); решаю сложные и запущенные задачи

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
