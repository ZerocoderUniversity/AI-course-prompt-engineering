
# Проект: Ассистент календаря и Учитель математики GPTs с Actions через Zapier

## Описание проекта
Этот проект демонстрирует полную реализацию интеграции GPT от OpenAI с внешними сервисами через платформу Zapier. Разработанный как часть портфолио, проект включает два интеллектуальных ассистента, настроенных для выполнения определённых задач:

1. **Ассистент календаря**: Умный помощник, который может управлять событиями в Google Calendar, включая создание, поиск и организацию событий с использованием естественного языка.
2. **Учитель математики**: Образовательный помощник, который генерирует задачи по математике для учеников, оценивает их ответы и сохраняет результаты в Google Sheets для дальнейшего анализа.

## Используемые технологии
- **OpenAI GPT (ChatGPT)**: Для обработки запросов на естественном языке и выполнения задач.
- **Zapier**: Для автоматизации и интеграции с внешними приложениями.
- **Google Calendar**: Для управления событиями.
- **Google Sheets**: Для хранения и анализа данных.

## Основные аспекты реализации

### 1. Ассистент календаря
- **Возможности**:
  - Создание детализированных событий в Google Calendar на основе запросов пользователя.
  - Поиск и отображение предстоящих событий.
  - Обработка часовых поясов и динамическое добавление описаний событий.
- **Примеры взаимодействия**:
  - Пример запроса: "Запланируй встречу с названием \"Конференция по ИИ\" на 15 марта 2025 года с 10:00 до 12:00."
  - Пользователи получают мгновенную обратную связь и подтверждение о созданных событиях.

### 2. Учитель математики
- **Возможности**:
  - Генерация персонализированных математических задач для учеников начальных классов.
  - Автоматическая проверка ответов учеников.
  - Запись имени ученика, задания, ответа и оценки в Google Sheets.
- **Примеры взаимодействия**:
  - Пример запроса: "Дай мне задачку по математике."
  - Ассистент взаимодействует пошагово, обеспечивая логическое и понятное взаимодействие.

## Ключевые особенности
- **Бесшовная интеграция**:
  - Использование функции Actions от Zapier для связи GPT с сервисами Google.
  - Отсутствие необходимости программирования для развёртывания.
- **Обработка ошибок**:
  - Встроенные инструкции для устранения проблем, таких как ошибки с часовыми поясами или неполные данные.
- **Масштабируемость**:
  - Возможность добавления новых интеграций, таких как Slack, Telegram или инструменты для управления проектами.

## Преодолённые вызовы
- **Управление часовыми поясами**:
  - Разработан структурированный подход для уточнения и управления расписанием событий в разных часовых поясах.
- **Динамическое хранение данных**:
  - Реализована надёжная интеграция с Google Sheets для беспроблемной записи и хранения данных.

## Ссылки на проект

### Ссылки на ассистентов
- **Тренер по математике**: [https://chatgpt.com/g/g-674474930bcc81919e0ea747372700da-trener-po-matematike-uchenika-mladshikh-klassov](https://chatgpt.com/g/g-674474930bcc81919e0ea747372700da-trener-po-matematike-uchenika-mladshikh-klassov)
- **Календарь**: [https://chatgpt.com/g/g-6744975a7ca481918c16123c44ab0074-kalendar](https://chatgpt.com/g/g-6744975a7ca481918c16123c44ab0074-kalendar)

### Файлы к проекту
- **Instructions from Zarier.txt**: [https://github.com/ZerocoderForstudents/Calendar-Assistant-Math-Teacher-GPTs-with-Actions-via-Zapier/blob/main/Instructions%20from%20Zarier.txt](https://github.com/ZerocoderForstudents/Calendar-Assistant-Math-Teacher-GPTs-with-Actions-via-Zapier/blob/main/Instructions%20from%20Zarier.txt)
- **Create Links to services.txt**: [https://github.com/ZerocoderForstudents/Calendar-Assistant-Math-Teacher-GPTs-with-Actions-via-Zapier/blob/main/Llinks%20to%20services.txt](https://github.com/ZerocoderForstudents/Calendar-Assistant-Math-Teacher-GPTs-with-Actions-via-Zapier/blob/main/Llinks%20to%20services.txt)
- **Text instructions with assistant behavior**: [https://github.com/ZerocoderForstudents/Calendar-Assistant-Math-Teacher-GPTs-with-Actions-via-Zapier/blob/main/Text%20instructions%20with%20assistant%20behavior](https://github.com/ZerocoderForstudents/Calendar-Assistant-Math-Teacher-GPTs-with-Actions-via-Zapier/blob/main/Text%20instructions%20with%20assistant%20behavior)
- [OpenAI GPT](https://openai.com/)
- [Zapier](https://zapier.com/)
- [Документация Zapier GPT Actions](https://actions.zapier.com/docs/platform/gpt/)

## Влияние на портфолио
Данный проект демонстрирует навыки в:
- Разработке и развёртывании ассистентов на основе ИИ.
- Интеграции ИИ с внешними платформами автоматизации.
- Решении реальных задач с использованием передовых технологий.

## Возможности для улучшения
- Добавление поддержки нескольких языков для расширения доступности.
- Введение аналитики для анализа математических результатов в Google Sheets.
- Исследование интеграции с голосовыми ассистентами для удобного использования.

---
## Скриншоты проекта:
<img src="https://github.com/ZerocoderForstudents/Calendar-Assistant-Math-Teacher-GPTs-with-Actions-via-Zapier/blob/main/screenshots/Open%20AI%203.png" alt="Иллюстрация к проекту" style="width:50%;"/>
<img src="https://github.com/ZerocoderForstudents/Calendar-Assistant-Math-Teacher-GPTs-with-Actions-via-Zapier/blob/main/screenshots/OpenAI.png" alt="Иллюстрация к проекту" style="width:50%;"/>
<img src="https://github.com/ZerocoderForstudents/Calendar-Assistant-Math-Teacher-GPTs-with-Actions-via-Zapier/blob/main/screenshots/Zapier1.png" alt="Иллюстрация к проекту" style="width:50%;"/>
<img src="https://github.com/ZerocoderForstudents/Calendar-Assistant-Math-Teacher-GPTs-with-Actions-via-Zapier/blob/main/screenshots/Zapier2.png" alt="Иллюстрация к проекту" style="width:50%;"/>
<img src="https://github.com/ZerocoderForstudents/Calendar-Assistant-Math-Teacher-GPTs-with-Actions-via-Zapier/blob/main/screenshots/%D0%9A%D0%B0%D0%BB%D0%B5%D0%BD%D0%B4%D0%B0%D1%80%D1%8C.png" alt="Иллюстрация к проекту" style="width:50%;"/>
