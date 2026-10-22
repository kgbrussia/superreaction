# Сайт Super Reaction (GitHub Pages)

Публичные страницы для RuStore и кнопки «Поделиться». Базовый URL в коде:

`https://kgbrussia.github.io/superreaction`

## Публикация

1. Создайте на GitHub репозиторий **superreaction** (или переименуйте — тогда обновите `SITE_BASE` в `scripts/texts/gen_legal.py` и `AppInfo.kt`, затем `python3 scripts/texts/gen_legal.py`).
2. Залейте папку `docs/` в корень репозитория (или весь проект и укажите источник Pages = ветка `main`, папка `/docs`).
3. Settings → Pages → Deploy from branch → `main` → `/docs`.
4. Проверьте в браузере: `https://kgbrussia.github.io/superreaction/privacy.html` и `https://kgbrussia.github.io/superreaction/terms.html`.

Перегенерация после правок текстов: `python3 scripts/texts/gen_legal.py`
