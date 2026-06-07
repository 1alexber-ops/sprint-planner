# Sprint Planner — paritet

## Правила работы
- После каждого изменения обновляй версию v0.XX в заголовке (title и h1) и увеличивай на 0.01
- Делай git commit после каждого изменения с описанием на русском
- Деплой: FIREBASE_TOKEN="$(cat ~/.firebase_token)" firebase deploy --project eparitet26 (токен хранится в ~/.firebase_token)
- После каждого деплоя увеличивай версию на 0.01
- URL: https://eparitet26.web.app

## Стек
- Одностраничный HTML (index.html)
- Firebase Hosting + Firestore
- Без фреймворков, чистый JS

## Команда
9 ролей: BA, Android, iOS, WEB Front, WEB/Mobile Api, Back Front, Back Api, QA, Дизайн

## Алгоритм спринтов
- Per-role scheduling с зависимостями (roleOrder)
- TOL = 5ч, MAX_SPRINTS = 50
- BA определяет порядок задач
