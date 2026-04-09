# Контрольная работа №3 — Безопасность FastAPI 🐝

Реализация системы аутентификации и авторизации в FastAPI с поддержкой JWT, ролевого доступа (RBAC) и защиты документации.

## 📋 Требования

- Python 3.11+
- pip

## 🚀 Установка и запуск

### 1. Клонирование репозитория

```bash
git clone <URL_репозитория>
cd <имя_папки>
```
### 2. Создание виртуального окружения

```bash
python -m venv venv
.\venv\Scripts\activate
```
### 3. Установка зависимостей

```bash
pip install -r requirements.txt
```
4. Настройка переменных окружения

```bash
copy .env.example .env
```
5. Запуск приложения

```bash
uvicorn main:app --reload
```
