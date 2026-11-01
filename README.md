# LifePulse

Персональная платформа для управления финансами, подписками и целями.

## 🚀 Возможности

- Учет транзакций из разных источников
- Автоматическое отслеживание подписок
- Бюджетирование с лимитами по категориям
- Финансовые цели с прогнозом достижения
- Умные автоматизации
- Аналитика и инсайты
- Прогноз денежных потоков

## 🏗 Архитектура

Микросервисная архитектура с использованием:
- Go (backend)
- PostgreSQL (основная БД)
- Redis (кэш и distributed locks)
- Apache Kafka/Redpanda (message broker)
- ClickHouse (аналитика)

## 📦 Микросервисы

- **Transaction Aggregator** - агрегация транзакций
- **Subscription Tracker** - учет подписок
- **Budget Service** - управление бюджетами
- **Notification Service** - уведомления
- **Analytics Service** - аналитика

## 🛠 Технологии

- Go 1.21+
- PostgreSQL 16
- Redis 7
- Redpanda (Kafka-compatible)
- ClickHouse
- Docker & Docker Compose
- Kubernetes (для продакшна)

## 📋 Требования

- Go 1.21+
- Docker & Docker Compose
- Make

## 🚀 Быстрый старт

### 1. Клонировать репозиторий

```bash
git clone https://github.com/atsybenko962/lifepulse.git
cd lifepulse