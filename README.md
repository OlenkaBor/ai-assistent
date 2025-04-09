Ссылка на проект https://web.telegram.org/k/#@Narodniieokna_bot

# ИИ-ассистент для компании по установке окон

## Описание проекта

Проект представляет собой интеллектуального ассистента, разработанного для автоматизации взаимодействия с клиентами компании, занимающейся установкой окон. Ассистент способен вести осмысленный диалог, отвечать на вопросы клиентов, основываясь на базе знаний компании, а также записывать клиентов на встречи и автоматически добавлять их в Google Календарь.

Этот инструмент значительно упрощает процесс коммуникации с клиентами, экономит время менеджеров и повышает эффективность работы компании.

---

## Функционал

1. **Осмысленное ведение диалога**  
   Ассистент использует нейросетевые технологии для ведения естественного диалога с клиентами. Он способен понимать контекст вопросов и предоставлять релевантные ответы.

2. **Ответы на вопросы по базе знаний**  
   База знаний содержит информацию о продуктах и услугах компании, включая цены, сроки выполнения работ, гарантии и другие важные детали. Ассистент может быстро находить нужную информацию и предоставлять её клиентам.

3. **Запись на встречу**  
   Клиенты могут записаться на встречу через ассистента. Для этого достаточно указать удобное время и дату.

4. **Интеграция с Google Календарь**  
   После записи клиента на встречу ассистент автоматически добавляет её в Google Календарь, что позволяет менеджерам легко отслеживать расписание.

---

## Используемые сервисы

### 1. **Qwen**
   - Платформа Qwen была использована для создания системного промпта и формирования базы знаний.
   - Промпт настроен таким образом, чтобы ассистент мог эффективно обрабатывать запросы клиентов и предоставлять точные ответы.

### 2. **Савви (Suvvy.ai)**
   - Сервис [Савви](https://suvvy.ai/) был выбран для создания и настройки ИИ-ассистента.
   - Платформа предоставляет инструменты для быстрой интеграции ассистента с различными каналами коммуникации и внешними сервисами.

### 3. **Telegram**
   - Ассистент доступен через Telegram-бота: [@Narodniieokna_bot](https://web.telegram.org/k/#@Narodniieokna_bot).
   - Telegram используется как основной канал взаимодействия с клиентами благодаря своей популярности и удобству использования.

---

## Установка и настройка

### Предварительные требования
- Доступ к Telegram API.
- Учетная запись Google с правами доступа к Google Календарю.
- Настроенный аккаунт в Suvvy.ai.

### Инструкция по запуску
1. **Создание бота в Telegram**  
   - Создайте нового бота через BotFather и получите токен API.
   
2. **Настройка базы знаний в Qwen**  
   - Подготовьте файл с информацией о продуктах и услугах компании.
   - Настройте системный промпт для обработки запросов клиентов.

3. **Интеграция с Suvvy.ai**  
   - Загрузите базу знаний в Suvvy.ai.
   - Настройте логику диалога и интеграцию с Telegram.

4. **Подключение Google Календаря**  
   - Настройте доступ к Google Calendar API.
   - Убедитесь, что ассистент имеет права на создание событий в календаре.

5. **Тестирование**  
   - Проверьте работу бота, отправив тестовые запросы через Telegram.
   - Убедитесь, что записи на встречу корректно добавляются в Google Календарь.

---

## Структура проекта

```
/ai-assistant-for-windows-installation
│
├── /docs                  # Документация проекта
│   ├── README.md          # Основное описание проекта
│   └── setup-guide.md     # Инструкция по установке
│
├── /data                  # Данные проекта
│   ├── knowledge-base.json # База знаний
│   └── prompts.json       # Системные промпты
│
├── /scripts               # Скрипты для настройки
│   ├── setup_telegram.py  # Настройка Telegram-бота
│   └── google_calendar.py # Интеграция с Google Календарем
│
└── config.json            # Конфигурационный файл
```

---

## Лицензия

Проект распространяется под лицензией [MIT License](LICENSE).

---

## Контакты

Если у вас есть вопросы или предложения, свяжитесь с нами:
- Email: support@narodnieokna.com
- Telegram: [@Narodniieokna_bot](https://web.telegram.org/k/#@Narodniieokna_bot)

---
```
