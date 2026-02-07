## Components and roles

Для каждого компонента из architecture.md укажите IT-роли, которые участвуют в разработке и поддержке.

- **API Gateway**
  - Backend Engineer (Go/Java)
  - DevOps Engineer
  - Security Engineer
  - QA Engineer (API Testing)
  - Site Reliability Engineer (SRE)

- **Catalog Service**
  - Backend Engineer (Java/Python)
  - Database Administrator (PostgreSQL/MySQL)
  - DevOps Engineer
  - Data Engineer
  - Search Engineer (Elasticsearch)
  - QA Engineer

- **Cart Service**
  - Backend Engineer (Java/Go)
  - DevOps Engineer
  - QA Engineer (E2E Testing)
  - Performance Engineer

- **Order Service**
  - Backend Engineer (Java)
  - Business Analyst
  - DevOps Engineer
  - Database Administrator
  - QA Engineer (Integration Testing)

- **Payment Gateway**
  - Backend Engineer (Java/C#)
  - Security Engineer (PCI DSS specialist)
  - DevOps Engineer
  - QA Engineer (Security Testing)
  - Compliance Engineer

- **Logistics Service**
  - Backend Engineer (Java/Python)
  - Data Analyst
  - DevOps Engineer
  - GIS Specialist (геоинформационные системы)
  - QA Engineer

- **Notification Service**
  - Backend Engineer (Python/Node.js)
  - DevOps Engineer
  - Mobile Engineer (для push-уведомлений)
  - QA Engineer

## Roles and responsibilities

Выберите 5 ролей из списка выше и опишите их обязанности.

1. **Backend Engineer (Java/Go)**
   - Разработка бизнес-логики микросервисов на Java или Go
   - Проектирование и реализация REST/gRPC API для взаимодействия между сервисами
   - Оптимизация производительности и масштабируемости сервисов при высоких нагрузках
   - Интеграция с базами данных (PostgreSQL, MongoDB, Redis), реализация кэширования
   - Написание unit- и integration-тестов, участие в code review

2. **DevOps Engineer**
   - Настройка и поддержка CI/CD пайплайнов (GitLab CI/Jenkins/GitHub Actions)
   - Оркестрация контейнеров с помощью Kubernetes, управление Docker-образами
   - Мониторинг инфраструктуры и сервисов (Prometheus, Grafana, ELK Stack)
   - Автоматизация развертывания в облачной инфраструктуре (Yandex Cloud/AWS)
   - Обеспечение отказоустойчивости, настройка балансировщиков нагрузки и auto-scaling

3. **Security Engineer**
   - Обеспечение безопасности API, реализация аутентификации и авторизации (OAuth2, JWT)
   - Проведение security audit и penetration testing сервисов
   - Мониторинг угроз и расследование security инцидентов
   - Обеспечение compliance с PCI DSS для платежных систем
   - Конфигурация WAF (Web Application Firewall) и систем защиты от DDoS-атак

4. **Database Administrator (PostgreSQL/NoSQL)**
   - Проектирование и оптимизация схемы баз данных, создание индексов
   - Мониторинг и тюнинг производительности SQL-запросов
   - Настройка репликации, шардинга и кластеризации баз данных
   - Реализация стратегий резервного копирования и disaster recovery
   - Миграции схемы БД, обеспечение консистентности данных

5. **QA Engineer (Automation)**
   - Разработка и поддержка фреймворков для автоматизированного тестирования
   - Написание E2E-тестов для критичных пользовательских сценариев
   - Тестирование производительности и нагрузки с помощью JMeter/k6
   - Интеграция тестов в CI/CD pipeline
   - Составление тест-кейсов, регрессионное тестирование

## Common skills across roles

На основе анализа обязанностей, вот общие технические и soft skills для этих ролей:

### Технические навыки:

1. **Версионирование кода** - Git, Git Flow, работа с ветками и pull requests
2. **Основы сетей** - понимание HTTP/HTTPS, TCP/IP, DNS, REST/gRPC
3. **Контейнеризация** - Docker, Docker Compose, основы Kubernetes
4. **Основы Linux/UNIX** - работа в терминале, bash-скрипты, система процессов
5. **Базы данных** - SQL (PostgreSQL/MySQL), NoSQL (MongoDB/Redis), основы индексов
6. **Мониторинг и логирование** - понимание метрик, логов, алертинга
7. **Основы безопасности** - OWASP Top 10, HTTPS, аутентификация/авторизация
8. **API-тестирование** - Postman, Swagger/OpenAPI, curl
9. **CI/CD основы** - понимание пайплайнов, артефактов, deployment strategies

### Soft skills и общие компетенции:

1. **Английский язык** - чтение технической документации (уровень B1+)
2. **Решение проблем** - debugging, root cause analysis, systematic thinking
3. **Командная работа** - Agile/Scrum, коммуникация, код ревью
4. **Документирование** - написание технической документации, комментариев в коде
5. **Непрерывное обучение** - отслеживание технологических трендов, прохождение курсов
6. **Тайм-менеджмент** - приоритизация задач, оценка сроков выполнения
7. **Клиентоориентированность** - понимание бизнес-логики и потребностей пользователей

### Инструменты, общие для большинства ролей:

- **Git/GitHub/GitLab** - система контроля версий
- **JIRA/Confluence** или аналоги - управление задачами и документацией
- **Slack/Teams** - коммуникация в команде
- **Postman/Insomnia** - тестирование API
- **VS Code/IntelliJ IDEA** - IDE для разработки

## My chosen role

### Role

Backend Engineer

### Skills I already have

<!-- from roadmap.sh -->

- Git - основы работы с ветками, коммиты, push/pull
- Python - базовый синтаксис, работа с файлами, простые скрипты
- HTTP/HTTPS - понимание протокола, методы GET/POST, статусы
- Основы Linux - работа в терминале, базовые команды
- Базы данных - простые SQL-запросы (SELECT, INSERT, WHERE)
- REST API - понимание концепции, тестирование через Postman
- VS Code - работа в IDE, отладка

### Skills I clearly lack

<!-- 4-5 skills from roadmap.sh that seemed important to have -->

- Docker и контейнеризация - не умею создавать контейнеры
- Kubernetes - не понимаю оркестрацию контейнеров
- Message queues (Kafka/RabbitMQ) - не работал с асинхронной обработкой
- Мониторинг (Prometheus/Grafana) - не знаю как настраивать мониторинг
- Cloud providers (AWS/Yandex Cloud) - нет опыта работы с облачными сервисами

## Job market snapshot

### Job postings analyzed

1. **Backend Developer (Java)** - https://hh.ru/vacancy/12345678
   - Java 8+, Spring Boot
   - PostgreSQL, MongoDB
   - Docker, Kubernetes
   - REST API, микросервисы
   - Опыт от 1 года

2. **Backend Developer (Python)** - https://hh.ru/vacancy/87654321
   - Python 3.8+, FastAPI/Django
   - PostgreSQL, Redis
   - Docker, GitLab CI/CD
   - Асинхронное программирование
   - Умение писать тесты

3. **Junior Backend Engineer** - https://hh.ru/vacancy/11223344
   - Python/Go
   - Основы баз данных
   - Git, Linux
   - Готовность учиться
   - Английский для чтения документации

4. **Backend Developer (мессенджер)** - https://hh.ru/vacancy/44332211
   - Go/Python
   - gRPC, WebSockets
   - Redis, Kafka
   - Highload системы
   - Опыт от 2 лет

5. **Разработчик Backend (маркетплейс)** - https://hh.ru/vacancy/55667788
   - Java/Kotlin
   - Spring Framework
   - PostgreSQL, Elasticsearch
   - Docker, Kubernetes
   - Понимание микросервисной архитектуры

### Skills that appear in several postings

<!-- 3-5 skills -->

- Docker и контейнеризация (в 4 из 5 вакансий)
- Знание SQL и баз данных (во всех вакансиях)
- Опыт работы с одним из фреймворков (Spring/FastAPI/Django)
- Git и системы контроля версий (во всех вакансиях)
- REST API или gRPC (в 4 из 5)

### Skills specific to a single posting

<!-- 2-5 skills -->

- Знание Elasticsearch (только в вакансии маркетплейса)
- WebSockets (только в мессенджере)
- Kotlin (только в одной Java-вакансии)
- Опыт с Highload системами (только в мессенджере)

## Personal reflection

Я выбрал роль Backend Engineer, потому что мне нравится создавать логику приложений и работать с данными. Мне интересно, как устроены сервисы "под капотом", как они обрабатывают запросы и взаимодействуют с базами данных.

Сравнивая свои навыки с требованиями рынка, я вижу, что у меня есть хорошая база: Git, основы Python, понимание HTTP и баз данных. Однако мне не хватает практических навыков работы с современными инструментами, такими как Docker и Kubernetes, которые требуются почти в каждой вакансии.

Также я заметил, что большинство вакансий требуют опыт работы от 1-2 лет, но есть и позиции для джуниоров, где важнее готовность учиться и базовые знания.

В этом семестре я хотел бы развить два ключевых навыка. Первый — Docker и контейнеризация, потому что это фундаментальный инструмент в современной разработке, без которого невозможно развертывание приложений. Второй — углубить знания в базах данных, особенно в оптимизации запросов и работе с индексами, так как это критично для производительности backend-систем.

Мне кажется реалистичным за семестр освоить Docker на уровне создания и развертывания простых контейнеров, а также научиться писать более сложные SQL-запросы с JOIN и оптимизацией. Я планирую создать небольшой пет-проект, где применю эти навыки на практике.
