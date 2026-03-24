# LUMIX Site

Статический сайт компании `ООО ЛЮМИКС`.

## Структура

- `index.html` — основной файл для публикации на домене
- `люмикс.html` — рабочая копия локального файла
- `DEPLOY.md` — краткий сценарий запуска

## Локальная проверка

Из папки проекта:

```bash
python3 -m http.server 8000
```

Открыть:

`http://localhost:8000/index.html`

## Git

Рекомендуемый базовый сценарий:

```bash
git init
git add .
git commit -m "Initial site release"
git branch -M main
git remote add origin <YOUR_REPO_URL>
git push -u origin main
```

## Публикация

Для домена и VPS основным входным файлом должен быть `index.html`.

