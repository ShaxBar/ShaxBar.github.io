# Портфолио: коллекция лендингов

**Live:** https://shaxbar.github.io/

Четыре лендинга на чистом HTML + Tailwind CSS (CDN), без сборки.

| Страница | Путь | Стиль |
|---|---|---|
| Портфолио-визитка | `/` | Тёмная тема, неон |
| SaaS «FlowBoard» | `/saas/` | Яркий, градиенты |
| Кофейня «Утро» | `/coffee/` | Тёплый, кремовый, serif |
| Курс «py.start» | `/course/` | EdTech, светлый, акцентные формы |

## Локальный запуск

```bash
python3 -m http.server 8000
# → http://localhost:8000
```

## Деплой

Хостинг — GitHub Pages из ветки `main`: каждый `git push`
обновляет сайт автоматически (~30 сек).

## Структура

```
├── index.html   # главная
├── saas/ coffee/ course/   # лендинги
└── img/         # превью карточек (*.webp) + og:image (preview.png)
```
