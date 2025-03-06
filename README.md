# Chime Backend

Бэкенд часть социальной платформы Chime.

## Возможности

- REST API для постов и медиа контента
- WebSocket сервер для чатов
- Система аутентификации и авторизации
- Загрузка изображений
- Отправка email-писем

## Технологии

- NestJS
- TypeScript
- PostgreSQL
- Prisma
- Passport
- Socket.IO

## Запуск приложения

### Требования:

- Node.js 18+
- PostgreSQL
- Docker (опционально)

### Локальная разработка:

1. Клонируйте репозиторий:

```bash
git clone https://github.com/Leroyalle/chime-backend.git
cd chime-backend
```

2. Создайте и заполните файл `.env`:

```bash
cp .env.example .env
```

3. Установите зависимости:

```bash
npm install
```

4. Запустите сервер разработки:

```bash
# Режим разработки
npm run start

# Watch режим
npm run start:dev
```

### Продакшн:

```bash
npm run build
npm run start:prod
```
