# Lab 8. Docker Compose (П08)

## Что было сделано
1. Установлен Docker Compose v2 .
2. Собран стек **Flask + Redis**: веб-приложение на Flask со счётчиком посещений.
3. Собран стек **Prometheus + Grafana** для мониторинга.
4. Проверена работа обоих стеков через `curl` и в браузере.

## Структура проектов
- `devops9compose/` — Flask + Redis.
- `devops9prom/` — Prometheus + Grafana.

## Скриншоты выполнения (папка `скрины`)

| Файл | Что изображено на скриншоте |
| :--- | :--- |
| `01-compose-install.png` | Установка Docker Compose v2  |
| `02-compose-install-end.png` | Окончание установки Compose |
| `03-flask-files.png` | Создание файлов Flask-проекта |
| `04-flask-build.png` | Процесс сборки образа Flask (скачивание зависимостей) |
| `05-flask-up.png` | Успешный запуск стека Flask + Redis  |
| `06-flask-browser.png` | Работа счётчика Flask в браузере |
| `07-flask-ps-curl.png` | Статус контейнеров и проверка счётчика через `curl`|
| `08-prom-compose-up.png` | Запуск стека Prometheus + Grafana |
| `09-prom-ps.png` | Статус контейнеров `prometheus` и `grafana` |
| `10-prometheus-browser.png` | Открытие Prometheus в браузере |
| `11-grafana-login.png` | Экран входа в Grafana |
| `12-grafana-home.png` | Главная страница Grafana после входа |
| `13-grafana-metric.png` | График метрики `prometheus_http_requests_total` в Grafana |
| `14-grafana-metric-raw.png` | Список метрик в Grafana в режиме Raw |
| `15-git-push-final.png` | Подготовка файлов и финальный `git push` |
| `16-git-pull-push.png` | Объединение репозиториев  и `git push` |
| `17-grafana-business-dashboard.png` | График бизнес-метрики (посещения сайта) в Grafana |
