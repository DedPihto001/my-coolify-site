# my-coolify-site

Учебный проект: статический сайт с автодеплоем через Coolify.

- VPS: Ubuntu, Docker, Coolify
- Деплой: Dockerfile (nginx) → Coolify → webhook на push в `main`

## Как восстановить
1. Установить Docker и Coolify на сервер
2. В Coolify создать ресурс из этого репозитория (build pack: Dockerfile, порт 80)
3. Добавить webhook из Coolify в Settings → Webhooks репозитория
