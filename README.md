<h1 align="center">Vlad Chernyshov</h1>

<p align="center">
  <b>Junior AI Engineer / Prompt Engineer</b><br>
  AI Agents · RAG · LangChain · LangFlow · FastAPI · n8n · Python
</p>

<p align="center">
  <a href="https://t.me/VladChernyshov"><img src="https://img.shields.io/badge/Telegram-%40VladChernyshov-26A5E4?style=flat-square&logo=telegram&logoColor=white" alt="Telegram"></a>
  <a href="https://vladaipro.com"><img src="https://img.shields.io/badge/Website-vladaipro.com-4C6EF5?style=flat-square&logo=googlechrome&logoColor=white" alt="Website"></a>
  <img src="https://img.shields.io/badge/Open%20to%20work-Junior%20AI%20Engineer-2EA44F?style=flat-square" alt="Open to work">
</p>

---

Привет! Я Владислав — начинающий AI-инженер: строю LLM-приложения, которые работают не в ноутбуке, а в проде.

Прошёл полный курс AI Engineering (27 модулей: prompt engineering, RAG, LangChain, LangFlow, деплой, файнтюнинг) и применил это на практике — спроектировал и поддерживаю инфраструктуру из нескольких AI-сервисов. Часть кода закрыта по NDA и бизнес-причинам, поэтому здесь лежат разборы архитектуры и изолированные демо на синтетических данных; полную картину готов разобрать на собеседовании.

Сильнее всего мне интересна не генерация текста сама по себе, а надёжность: как сделать так, чтобы агент не выдумывал факты, чтобы пайплайн честно останавливался при сбое, и чтобы внешний текст не превращался в инъекцию в промпт.

## Стек

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" alt="LangChain">
  <img src="https://img.shields.io/badge/LangFlow-FF3C78?style=flat-square" alt="LangFlow">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI">
  <img src="https://img.shields.io/badge/ChromaDB-FFB300?style=flat-square" alt="ChromaDB">
  <img src="https://img.shields.io/badge/OpenAI%20API-412991?style=flat-square&logo=openai&logoColor=white" alt="OpenAI API">
  <img src="https://img.shields.io/badge/Claude%20API-D97757?style=flat-square&logo=anthropic&logoColor=white" alt="Claude API">
  <img src="https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white" alt="n8n">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" alt="SQLite">
  <img src="https://img.shields.io/badge/Telegram%20Bot%20API-26A5E4?style=flat-square&logo=telegram&logoColor=white" alt="Telegram Bot API">
</p>

**Направления:** agentic-системы и tool calling · RAG, embeddings, векторный поиск · structured output и anti-hallucination дизайн · LLM-автоматизация в Telegram

## Проекты

| Проект | Что это показывает | Стек |
|---|---|---|
| **[ai-team-demo](https://github.com/v5107005-del/ai-team-demo)** | Case study боевого конвейера: многоэтапная генерация с циклом доработки, quality gates по порогам, детерминированный фактчекинг в регулируемой нише, найденная и закрытая prompt-injection уязвимость | Agentic pipeline, structured output, fact-checking |
| **[rag-assistant](https://github.com/v5107005-del/rag-assistant)** | Полный RAG-пайплайн от загрузки документов до ответа с источниками и честным «в базе знаний этого нет». CLI и веб-интерфейс поверх одного ядра | Python, ChromaDB, OpenAI, FastAPI, Docker |
| **[digital-client-profile](https://github.com/v5107005-del/digital-client-profile)** | LangFlow MVP: сырая переписка → структурированный JSON-профиль по строгой схеме. Недостающие поля помечаются как insufficient_data, а не выдумываются | LangFlow, JSON Schema, custom Python component |
| **[finance-ledger-agent](https://github.com/v5107005-del/finance-ledger-agent)** | Агент, который сам выбирает инструмент из запроса на естественном языке — паттерн agent + tools вместо if/else-роутинга | LangChain, tool calling, Docker |
| **[prompt-engineering-examples](https://github.com/v5107005-del/prompt-engineering-examples)** | Карта пройденного курса: RAG, оценка качества через RAGAS, масштабирование, деплой, файнтюнинг, LangChain и LangFlow | Python, RAGAS, n8n, LangFlow |

## Статистика

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=v5107005-del&show_icons=true&hide_border=true&include_all_commits=true&count_private=true&theme=transparent" alt="GitHub stats" height="150">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=v5107005-del&layout=compact&hide_border=true&langs_count=8&theme=transparent" alt="Top languages" height="150">
</p>

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=v5107005-del&column=7&margin-w=6&margin-h=6&no-frame=true&theme=flat" alt="Trophies">
</p>

## Чем занимаюсь сейчас

- Довожу RAG-пайплайн до измеримого качества: оценка через RAGAS (Faithfulness, Context Precision) вместо «на глаз»
- Изучаю LangGraph — управляемые графы состояний вместо линейных цепочек
- Добавляю гибридный поиск (dense + BM25) и локальные эмбеддинги через Ollama, чтобы демо запускались без платного ключа
- Пишу разбор найденной prompt-injection уязвимости и её фикса

## Контакты

- Telegram — [@VladChernyshov](https://t.me/VladChernyshov)
- Сайт — [vladaipro.com](https://vladaipro.com)
- Открыт к позициям Junior AI Engineer / Prompt Engineer и к проектной работе

<sub>Все примеры в репозиториях запускаются на синтетических данных. Ключи, клиентские данные и коммерческий код не публикуются.</sub>
