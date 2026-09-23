# 🚀 Полезный код и практические проекты для разработчиков

**useful-code-lab** — это открытое портфолио с практическими проектами, лабораториями, учебными материалами и бесплатными курсами для разработчиков.

Здесь можно не просто посмотреть исходный код, а **разобраться, как решаются реальные инженерные задачи**: от разработки API и работы с базами данных до микросервисов, высоких нагрузок, Kubernetes, DevOps, AI/ML и архитектуры больших систем.

> **Полезный код. Реальные задачи. Практические навыки.**

---

## 🎯 Что вы найдёте здесь

Репозиторий создан как **практическая карта развития разработчика**.

Вместо разрозненных примеров здесь собраны проекты, которые позволяют изучать технологии через работающий код и воспроизводимые эксперименты.

### Вы сможете:

* изучать готовые примеры архитектуры;
* запускать проекты локально и экспериментировать с ними;
* разбирать production-подходы на практических сценариях;
* сравнивать разные способы решения одной задачи;
* изучать Go, Python, PHP, JavaScript, TypeScript и другие технологии;
* разбираться с PostgreSQL, Redis, MongoDB, Kafka и ClickHouse;
* изучать микросервисную архитектуру;
* экспериментировать с Kubernetes и DevOps;
* исследовать производительность и конкурентность;
* изучать observability и OpenTelemetry;
* разбирать AI/ML и LLM-инструменты;
* использовать проекты как основу для собственных приложений;
* готовиться к техническим собеседованиям;
* находить бесплатные курсы и дополнительные материалы.

---

# 🧑‍💻 Практическое портфолио

Главная часть проекта — не просто список технологий, а **набор практических инженерных решений**.

## 🐹 Go и backend

В репозиториях можно посмотреть реальные примеры:

* REST API;
* gRPC;
* WebSocket;
* JWT и RBAC;
* конкурентное программирование;
* Worker Pool;
* Kafka;
* RabbitMQ;
* NATS;
* Redis;
* PostgreSQL;
* MongoDB;
* Saga;
* CQRS;
* Event-Driven Architecture;
* Transactional Outbox;
* rate limiting;
* distributed locks;
* идемпотентность;
* graceful shutdown;
* профилирование и оптимизацию.

### Избранные проекты

* [Go REST API Starter](https://github.com/useful-code-lab/go-rest-api-starter-jwt-postgresql) — готовая основа REST API с JWT, PostgreSQL, Swagger, Docker, тестами и мониторингом.
* [Go Event-Driven Order Processing](https://github.com/useful-code-lab/go-event-driven-order-processing) — пример микросервисной обработки заказов через gRPC, Kafka и Redis.
* [Go Concurrent Task Runner](https://github.com/useful-code-lab/go-concurrent-task-runner) — практический пример Worker Pool, goroutines, channels, context и graceful shutdown.
* [Go Concurrency Patterns](https://github.com/useful-code-lab/go-concurrency-patterns-highload) — набор паттернов конкурентного программирования.
* [Go Performance Lab](https://github.com/useful-code-lab/go-performance-lab) — практическая работа с CPU, памятью, goroutines, блокировками и pprof.
* [Go Internals Practical Guide](https://github.com/useful-code-lab/go-internals-practical-guide) — изучение runtime, scheduler GMP, GC, allocator и escape analysis.
* [Go Neural Network Lab](https://github.com/useful-code-lab/go-neural-network-lab) — реализация нейросети на Go без сторонних ML-библиотек.

---

# 🗄️ PostgreSQL и базы данных

Отдельное направление портфолио — практическое исследование баз данных.

Здесь можно изучать:

* индексы;
* EXPLAIN ANALYZE;
* транзакции;
* уровни изоляции;
* блокировки;
* deadlocks;
* optimistic locking;
* pessimistic locking;
* replication;
* failover;
* sharding;
* partitioning;
* JSONB;
* аналитические запросы;
* оптимизацию SQL.

### Проекты

* [PostgreSQL Query Optimization Lab](https://github.com/useful-code-lab/postgresql-query-optimization-lab)
* [PostgreSQL Concurrent Transactions](https://github.com/useful-code-lab/postgresql-concurrent-transactions)
* [PostgreSQL HA, Replication & Sharding Lab](https://github.com/useful-code-lab/postgres-ha-replication-sharding-lab)
* [PostgreSQL Analytics Toolkit](https://github.com/useful-code-lab/postgresql-analytics-toolkit)
* [Cache Performance Lab](https://github.com/useful-code-lab/cache-performance-lab)

**Практическая польза:** можно не только прочитать о производительности PostgreSQL, но и воспроизвести эксперименты самостоятельно.

---

# ☁️ Kubernetes, DevOps и инфраструктура

Проекты позволяют изучать инфраструктуру современных приложений на практике:

* Kubernetes;
* Helm;
* Istio;
* Docker;
* Ansible;
* Prometheus;
* Grafana;
* OpenTelemetry;
* service mesh;
* Canary Deployment;
* HPA;
* автоматическое восстановление;
* CI/CD;
* мониторинг и диагностику.

### Проекты

* [Kubernetes Fullstack Go Operator](https://github.com/useful-code-lab/kubernetes-fullstack-go-operator)
* [Kubernetes + Istio Microservices Lab](https://github.com/useful-code-lab/kubernetes-istio-microservices-lab)
* [Kubernetes Auto-Healing Incident Explorer](https://github.com/useful-code-lab/kubernetes-auto-healing-incident-explorer)
* [Kubernetes Microservice Helm + Istio + Redis](https://github.com/useful-code-lab/kubernetes-microservice-helm-istio-redis)
* [DevOps Go + Ansible + Docker + Monitoring](https://github.com/useful-code-lab/devops-go-ansible-docker-monitoring)

---

# 📨 Event-Driven и распределённые системы

Отдельный пласт проектов посвящён системам, в которых сервисы взаимодействуют через события и очереди.

Можно изучать:

* Apache Kafka;
* RabbitMQ;
* NATS;
* Event-Driven Architecture;
* Saga;
* CQRS;
* Eventual Consistency;
* Transactional Outbox;
* Retry Queue;
* Dead Letter Queue;
* идемпотентность;
* обработку дубликатов;
* асинхронное взаимодействие сервисов.

### Проекты

* [Reliable Event Pipeline](https://github.com/useful-code-lab/reliable-event-pipeline-go-kafka)
* [Saga + CQRS + RabbitMQ](https://github.com/useful-code-lab/go-saga-cqrs-rabbitmq-postgresql)
* [Kafka + ClickHouse Event Processing](https://github.com/useful-code-lab/kafka-clickhouse-event-processing-pattern)
* [Event-Driven Notification Service](https://github.com/useful-code-lab/go-event-driven-notification-service)
* [Concurrent Transaction Processing](https://github.com/useful-code-lab/concurrent-transaction-processing-go)

---

# 🐍 Python, аналитика и AI

Python-направление объединяет разработку, анализ данных и современные AI-технологии.

Здесь можно найти материалы по:

* Python;
* Pandas;
* анализу данных;
* оптимизации;
* параллельному программированию;
* Machine Learning;
* нейросетям;
* LLM;
* AI-ассистентам;
* prompt engineering.

### Практические проекты

* [Marketplace Sales Analytics](https://github.com/useful-code-lab/marketplace-sales-analytics) — анализ продаж, RFM-сегментация, поиск аномалий и визуализация данных.
* [Stepik AI Quiz Generator](https://github.com/useful-code-lab/stepik-ai-quiz-generator) — генерация интерактивных учебных заданий с использованием LLM.

---

# 🏢 Enterprise-разработка

В портфолио представлены проекты, показывающие подходы, которые применяются при создании крупных приложений.

### PHP / Symfony

* [Symfony Billing Architecture](https://github.com/useful-code-lab/Symfony-billing-architecture)

Практический пример биллинга с DDD, Hexagonal Architecture, CQRS, Messenger, Doctrine и PostgreSQL.

### Laravel

* [Laravel 13 Marketplace Backend](https://github.com/useful-code-lab/laravel13-marketplace-backend)

Backend мультивендорного маркетплейса с DDD, CQRS, REST API, транзакциями, кэшированием и защитой от race condition.

### Vue / TypeScript

* [Vue 3 Enterprise HR Architecture](https://github.com/useful-code-lab/vue3-enterprise-hr-architecture)

Enterprise frontend с Vue 3, TypeScript, FSD, Pinia, RBAC, MSW, CRUD, тестированием и accessibility.

---

# 🧪 Лаборатории

Отдельная ценность репозитория — **лабораторный подход**.

Многие проекты можно использовать как небольшие инженерные эксперименты:

```text
Запустил → изменил → нагрузил → измерил → сравнил → сделал вывод
```

Например:

**Производительность**

CPU → memory → goroutines → locks → latency → pprof

**PostgreSQL**

Query → EXPLAIN → Index → Lock → Transaction → Optimization

**Kubernetes**

Deployment → Service → Ingress → HPA → Istio → Observability

**Event-driven**

Producer → Kafka → Consumer → Retry → DLQ → Idempotency

Такой подход помогает переходить от теоретического понимания технологии к практическому опыту.

---

# 📚 Бесплатные курсы

Помимо собственных практических проектов, здесь собрана подборка бесплатных курсов.

## Go

* [Middle Go-разработчик](https://stepik.org/course/251758/promo)
* [Продвинутый Golang: техническое собеседование](https://stepik.org/course/270441/promo)
* [Go-программист: программы, боты и веб-сервисы](https://stepik.org/course/270676/promo)

## Python

* [Квест: Параллельный Python](https://stepik.org/course/256069/promo)
* [Python Developer Quest](https://stepik.org/course/262590/promo)
* [Python и архитектура: Middle → Senior](https://stepik.org/course/253238/promo)
* [Python Senior: архитектура и практика](https://stepik.org/course/262593/promo)
* [Метапрограммирование Python](https://stepik.org/course/255404/promo)
* [Профилирование и оптимизация Python и Go](https://stepik.org/course/262583/promo)

## AI / ML

* [Современные нейросети](https://stepik.org/course/262559/promo)
* [AI и ML в реальных проектах](https://stepik.org/course/251835/promo)
* [AI/ML-чат-ассистенты для бизнеса](https://stepik.org/course/270671/promo)
* [Prompt Engineering](https://stepik.org/course/270672/promo)
* [Устройство Ollama и LLM](https://stepik.org/course/262612/promo)
* [Разработка нейросетей: от ядра до продакшена](https://stepik.org/course/263112/promo)

## Backend и архитектура

* [gRPC на Python и Go](https://stepik.org/course/259844/promo)
* [Event-Driven микросервисы](https://stepik.org/course/270669/promo)
* [Продвинутый SQL](https://stepik.org/course/261266/promo)
* [ClickHouse и большие данные](https://stepik.org/course/261244/promo)

## DevOps

* [Kubernetes-квест](https://stepik.org/course/259848/promo)
* [DevOps и CI/CD](https://stepik.org/course/255400/promo)
* [OpenTelemetry в реальном проекте](https://stepik.org/course/270667/promo)
* [OpenTelemetry для инженеров](https://stepik.org/course/253100/promo)

## Другие технологии

* [Middle JavaScript Developer](https://stepik.org/course/269119/promo)
* [TypeScript Middle+](https://stepik.org/course/259107/promo)
* [React FSD](https://stepik.org/course/255412/promo)
* [Java и многопоточность](https://stepik.org/course/269120/promo)
* [C# для продвинутых](https://stepik.org/course/270442/promo)
* [Lua и Roblox](https://stepik.org/course/266536/promo)

---

# 🗺️ Как использовать этот GitHub

Не обязательно изучать всё подряд.

Выберите конкретную цель и используйте репозитории как практический маршрут.

### Хочу изучить Go

**Go → REST API → PostgreSQL → concurrency → gRPC → Kafka → Kubernetes → observability**

### Хочу усилить Python

**Python → архитектура → параллельность → оптимизация → Data Science → AI/ML**

### Хочу разобраться в микросервисах

**REST → gRPC → Kafka/RabbitMQ → Event-Driven → Saga → CQRS → Kubernetes**

### Хочу изучить PostgreSQL

**SQL → индексы → EXPLAIN → транзакции → locks → replication → HA → sharding**

### Хочу разобраться в DevOps

**Docker → CI/CD → Ansible → Kubernetes → Helm → Istio → Prometheus → Grafana → OpenTelemetry**

### Хочу изучать AI

**Нейросети → LLM → Prompt Engineering → AI-ассистенты → интеграция в приложения**

---

# 💡 Что можно взять из проектов

Каждый репозиторий можно использовать по-разному.

### 📖 Как учебник

Изучить структуру проекта, архитектуру и реализацию отдельных компонентов.

### 🔬 Как лабораторную работу

Запустить проект, изменить параметры и посмотреть, как меняется поведение системы.

### 🧩 Как основу собственного проекта

Взять архитектурный подход, конфигурацию или отдельный компонент и адаптировать его под свою задачу.

### 💼 Как материал для портфолио

Использовать проекты для демонстрации практических навыков и обсуждения архитектурных решений на техническом собеседовании.

### 🧠 Как шпаргалку

Вернуться к нужному репозиторию, когда понадобится конкретный паттерн, технология или инженерное решение.

---

# ⭐ Почему стоит сохранить репозиторий

**useful-code-lab** можно использовать как персональную техническую библиотеку.

Вместо поиска десятков разрозненных примеров здесь можно найти:

* готовый пример;
* практический эксперимент;
* архитектурный шаблон;
* лабораторную работу;
* учебный курс;
* идею для собственного проекта;
* материал для подготовки к собеседованию.

Репозиторий развивается и постепенно превращается в **карту практических знаний для разработчика**.

---

# 🧭 С чего начать

Если вы впервые попали сюда, можно начать с одного из направлений:

| Цель            | С чего начать                         |
| --------------- | ------------------------------------- |
| 🐹 Go           | REST API → concurrency → gRPC         |
| 🐍 Python       | Python → оптимизация → AI/ML          |
| 🏗️ Архитектура | DDD → CQRS → микросервисы             |
| 📨 Event-Driven | Kafka → RabbitMQ → Saga               |
| 🗄️ PostgreSQL  | SQL → индексы → транзакции            |
| ☁️ Kubernetes   | Kubernetes → Helm → Istio             |
| 📊 Data         | Python → Pandas → аналитика           |
| 🤖 AI           | LLM → Prompt Engineering → AI-системы |
| ⚡ Performance   | profiling → pprof → optimization      |
| 🔐 Security     | TLS/mTLS → JWT → RBAC                 |

---

# 👨‍💻 О проекте

**useful-code-lab** создаётся как открытая техническая библиотека, где знания представлены не только в виде текста, но и через **код, эксперименты и воспроизводимые сценарии**.

Основная идея проста:

> **Не просто прочитать о технологии — запустить её, изменить, измерить и понять, как она работает.**

Если проект оказался полезен — ⭐ поставьте Star и сохраните репозиторий, чтобы вернуться к нему позже.

---

## ⚠️ Об образовательных материалах

Ссылки на внешние курсы и материалы ведут на сторонние площадки. Условия бесплатного доступа, содержание и доступность курсов могут изменяться их авторами и владельцами платформ.

Практические проекты этого профиля предназначены для обучения, экспериментов и изучения инженерных подходов.

---

**Полезный код → Практический эксперимент → Реальный навык.**
