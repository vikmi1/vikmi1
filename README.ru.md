[English](https://github.com/vikmi1/vikmi1/blob/main/README.md) · [Deutsch](https://github.com/vikmi1/vikmi1/blob/main/README.de.md) · **Русский**

<!-- Впишите имя: например «# Виктор …, Python-разработчик» -->
# Python-разработчик · бэкенд, Telegram-боты, LLM-интеграции

Делаю сервисы и приложения, в которых работает ИИ: от прототипа до готового продукта
с документацией, тестами и деплоем в Docker. Основной язык — Python, для мобильной
части — Kotlin. Подключаю Claude и OpenAI, строю RAG по документам, распознаю речь,
генерирую PDF, храню данные в PostgreSQL и SQLite.

## Стек

| Область | Технологии |
|---|---|
| Языки | Python, Kotlin, SQL, HTML/CSS, JavaScript |
| Бэкенд | FastAPI, Flask, Pydantic, Jinja2, REST API, WebSocket |
| AI / LLM | Anthropic Claude API, OpenAI API, Whisper, RAG (ChromaDB, эмбеддинги), промпт-инжиниринг |
| Telegram-боты | aiogram 3 (FSM), pyTelegramBotAPI |
| Данные | PostgreSQL, SQLite |
| Интерфейсы | Android (Jetpack Compose), Tkinter, Rich (терминал) |
| Инструменты | Docker, docker-compose, Git, GitHub, pytest, WeasyPrint |

## Избранные проекты

| Проект | Что делает | Стек |
|---|---|---|
| [**voice-to-messenger**](https://github.com/vikmi1/voice-to-messenger) | Android-приложение: надиктовал — получил готовое сообщение в нужном тоне. Живой перевод собеседника в наушник, кнопка-пузырь поверх мессенджеров, админ-панель с журналом расхода токенов | Kotlin, Jetpack Compose, Flask, WebSocket, Whisper, OpenAI / Anthropic, Docker |
| [**MVP-Lead-Manager**](https://github.com/vikmi1/MVP-Lead-Manager) | Сервис приёма заявок: форма для клиента, панель менеджера, уведомления на email и в Google Sheets, экспорт CSV/JSON, учёт требований DSGVO | FastAPI, Pydantic v2, SQLite, Jinja2 |
| [**Bot-with-Memory**](https://github.com/vikmi1/Bot-with-Memory) | Telegram-бот с кратковременной памятью (история + суммаризация) и долговременной: RAG по загруженным PDF, DOCX и TXT с указанием источников | aiogram 3, OpenAI, ChromaDB, pytest |
| [**claude-terminal-chat**](https://github.com/vikmi1/claude-terminal-chat) | Терминальный чат с Claude: режим Thinking, потоковый вывод, выбор модели, история между сессиями | Anthropic SDK, Rich |
| [**table_booking**](https://github.com/vikmi1/table_booking) | Десктоп-приложение для ресторана: карта зала, бронирования, контроль пересечений по времени, мастер первичной настройки БД | Tkinter, PostgreSQL, psycopg2 |
| [**invoicemaker**](https://github.com/vikmi1/invoicemaker) | Генератор PDF-счетов из CSV/JSON по HTML-шаблонам с расчётом НДС и пакетной обработкой | WeasyPrint, HTML/CSS |

Ещё: [Team-task-bot](https://github.com/vikmi1/Team-task-bot) — бот для командных задач со статусами и экспортом в CSV,
[Travel_wallet_currency_Bot](https://github.com/vikmi1/Travel_wallet_currency_Bot) — кошелёк путешественника с курсами валют через API.

## Как это выглядит

| Панель менеджера заявок | Карта зала в бронировании |
|---|---|
| [![Панель менеджера](https://raw.githubusercontent.com/vikmi1/MVP-Lead-Manager/master/screenshots/admin.png)](https://github.com/vikmi1/MVP-Lead-Manager) | [![Карта зала](https://raw.githubusercontent.com/vikmi1/table_booking/main/screenshots/booking_map.png)](https://github.com/vikmi1/table_booking) |

## Чем могу быть полезен

- Telegram-бот под задачу бизнеса: заявки, задачи, справочник, ответы по документам компании.
- Подключение LLM к продукту: генерация текстов и отчётов, распознавание речи, поиск по документам (RAG).
- Небольшой бэкенд на FastAPI или Flask с базой данных, API и панелью администратора.
- Автоматизация рутины: генерация PDF, выгрузки в CSV и Google Sheets, уведомления.

## Контакты

<!-- Добавьте свои контакты, например:
- LinkedIn: https://www.linkedin.com/in/...
- Telegram: https://t.me/...
- Email: ...
- Резюме: ссылка на PDF
-->
- GitHub: [github.com/vikmi1](https://github.com/vikmi1)
