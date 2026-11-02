# Мониторинг «Живой стали»

Внешний мониторинг [stal.neuroimpuls.ru](https://stal.neuroimpuls.ru) на [Upptime](https://upptime.js.org):
GitHub Actions каждые 5 минут проверяет сайт, `/api/health` и `/api/ready`, а `/api/health` — ещё
и с точки в России через Globalping. Сбой открывает задачу в этом репозитории и шлёт тревогу
в служебный чат Telegram; восстановление закрывает задачу.

Настройки — `.upptimerc.yml`. Решение — ADR-008 в репозитории проекта (дополнен 2026-11-02).
