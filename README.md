# Архивная копия статьи OTUS — «Пример выпускного проекта курса „DevOps практики и инструменты“»

> 🔗 **Оригинал:** https://otus.ru/nest/post/692/
>
> Автор: Андрей Павленко · опубликовано 25.04.2019 в блоге OTUS.
> **Все права на текст и изображения принадлежат OTUS и автору статьи.** Эта копия
> сохранена исключительно в личных целях (защита от удаления) и опубликована в
> объёме цитирования.

Живая страница: https://ozyab09.github.io/otus-devops-post-692/

## О чём статья

Выпускной проект слушателя курса «DevOps практики и инструменты» (Вячеслав Егоров):
балансировщик нагрузки на стеке **Docker Swarm + Traefik + ELK**, инфраструктура
поднимается через **Terraform** в Shared gitlab-runner.

## Структура репозитория

```
.
├── index.html      # одностраничная копия статьи (GitHub Pages)
├── assets/
│   ├── cover.png   # обложка
│   ├── pipeline.jpg# схема pipeline
│   └── traefik.jpg # схема работы Traefik
└── README.md
```

## Как это работает

Статический одностраничник на чистом HTML/CSS без сборки. GitHub Pages отдаёт
`index.html` из корня ветки `main`.

Чтобы включить Pages вручную: *Settings → Pages → Source: Deploy from a branch →
Branch: main / (root) → Save*.

## Локальный запуск

```bash
python3 -m http.server 8000
# открыть http://localhost:8000
```
