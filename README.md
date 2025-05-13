# Магазин пельменей "Момо"

Финальный проект по курсу Docker.

## Как запустить проект

1. Запустите приложение:
   ```bash
   docker-compose up -d
   ```

2. Доступ к приложению:
   - Фронтенд: http://localhost
   - API бэкенда: http://localhost:8081

## Как собрать образы вручную

```bash
# Сборка бэкенда
docker build -t momo-store-backend:latest ./backend

# Сборка фронтенда
docker build -t momo-store-frontend:latest ./frontend
```
