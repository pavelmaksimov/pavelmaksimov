## Hi there 👋

<!--
**pavelmaksimov/pavelmaksimov** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
--># Pavel Maksimov

**Python Developer | Backend Engineer**

## 🚀 Pinned Projects

### 🛠️ Linters

Я создал несколько статических анализаторов для управления сложностью 
и контроля архитектурных ограничений в Python-проектах.

<details><summary>🧱 bounded-contexts-linter - Проверяет изоляцию "ограниченных контекстов" Domain-Driven Design.
</summary>
https://github.com/pavelmaksimov/bounded-contexts-linter

Проверяет, что зависимости между модулями возникают только внутри одного bounded context,
предотвращая несанкционированные импорты между доменами.
Позволяет явно определять shared kernel и shared scope для общих модулей.
Линтер поддерживает настройку через TOML-файл.
Поддерживает работу как отдельный инструмент и как плагин для flake8.
</details>

<details><summary>🏷️ domain-types-linter - Проверяет ограничение на использование приминитивных типов в 
аннотациях.</summary>
https://github.com/pavelmaksimov/domain-types-linter

Следит за тем, чтобы в аннотациях использовались только доменно-специфичные типы, 
а не универсальные (str, int и т.д.). 
Анализирует аннотации типов и выявляет нарушения: использование универсальных типов, 
их алиасов или generic-типов без доменных параметров. 
Поддерживает работу как отдельный инструмент и как плагин для flake8.
</details>

<details><summary>💉 di-linter - Обнаруживает инъекции зависимостей (Dependency Injection).</summary>
https://github.com/pavelmaksimov/di-linter

Реализует проверку соблюдения принципа инверсии зависимостей. 
Инструмент определяет случаи, когда зависимости создаются или используются напрямую в функциях, а не передаются извне.
Подходит проектам, где нужно внедрять зависимости через DI-контейнер 
или поддерживать принципы чистой архитектуры, делая код более тестируемым и поддерживаемым. 
Линтер поддерживает настройку через TOML-файл.
Поддерживает работу как отдельный инструмент и как плагин для flake8.
</details>

<details><summary>🍰 layers-linter - Проверяет соблюдение слоистой архитектуры.</summary>
https://github.com/pavelmaksimov/layers-linter

Предназначен для проверки соблюдения архитектурных ограничений, связанных с:
1. разделением модулей по их техническим ролям и контроль направления зависимостей между ними;
Анализирует импорты между модулями и предупреждает, 
когда направление зависимости между слоями не соответствуют заданнам направлениям;
3. ограничением на использование библиотек в определенных слоях;
Анализирует импорты библиотек и предупреждает, если библиотека импортирована в ограниченном для неё, слое;

Для настройки используется TOML-файл, где описываются слои и направление зависимостей. 
Особенно полезен для командной работы над сложными проектами.
Поддерживает работу как отдельный инструмент и как плагин для flake8.
</details>

### ⚙️ Tools
<details>
<summary>🏛️ project-architecture-template - Шаблон слоистой архитектуры для Python проектов.</summary>
https://github.com/pavelmaksimov/project-architecture-template

Содержит предварительно настроенную структуру проекта, конфигурационные файлы и базовые модули для быстрого старта. 
Включает:
- Документированную слоистую архитектуру 
- Настроенные линтеры
- Настроенные фабрики и фикстуры для тестов
- CI/CD конфигурации для GitLab
- Подключение к бд Postgres
- Alembic для миграций бд
- и др.
</details>

<details>
<summary>🏗️ sqlalchemy-fastapi-endpoint-factory - Генератор CRUD эндпоинтов</summary>
https://github.com/pavelmaksimov/sqlalchemy-fastapi-endpoint-factory

Инструмент для автоматической генерации CRUD-эндпоинтов FastAPI на основе моделей SQLAlchemy. 
Позволяет быстро создавать REST API для работы с данными без ручного описания маршрутов. 
Пример использования — одна строка для генерации эндпоинта по любой модели Pydantic. 
Подходит для прототипирования и ускорения разработки сервисов на FastAPI и SQLAlchemy.
</details>

### 📡 API Clients

🛍️ [tapi-yandex-market](https://github.com/pavelmaksimov/tapi-yandex-market) - Python клиент для API Яндекс.Маркета.

📢 [tapi-yandex-direct](https://github.com/pavelmaksimov/tapi-yandex-direct) - Python клиент для API Яндекс.Директ.

📈 [tapi-yandex-metrika](https://github.com/pavelmaksimov/tapi-yandex-metrika) - Python Клиент всех для API Яндекс.Метрика.

### Other

🌊 [FlowMaster](https://github.com/pavelmaksimov/FlowMaster) - Фреймворк для построения ETL/ELT пайплайнов по YAML-конфигурации.

🧠 [algorithms](https://github.com/pavelmaksimov/algorithms) - Записывал решения и ошибки при решении алгоритмических 
задач

📊 [attributions](https://github.com/pavelmaksimov/attributions) - Инструмент для атрибуции в маркетинговой аналитике.

---

## 📬 Contact Me

Telegram: [@pavel_maksimow](https://t.me/pavel_maksimow)
