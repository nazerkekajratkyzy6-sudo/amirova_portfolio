# Терезе — портфолио мұғалімі Амирова Айнур Бақытбекқызы

Статикалық сайт (HTML + JS, сборка не нужна): «Таныстырылым» (5 минут) және «Толық портфолио».
«Үздік ауыл мұғалімі–2026», I кезең.

```
index.html   — весь сайт (CSS/JS/шрифты внутри)
data.js      — все тексты, подписи, список документов и фото
media/       — p (фото), t (превью), d (документы), v (видео), a (музыка)
vercel.json  — настройки Vercel (без сборки, кэш медиа)
```

## Загрузка на GitHub
**Вариант A — GitHub Desktop (проще всего, для всех 334 файлов сразу)**
1. Установить GitHub Desktop → File → New repository (например `amirova-portfolio`), Local path — любая папка.
2. Распаковать `Amirova_portfolio_github.zip` и скопировать всё содержимое в папку репозитория.
3. Commit to main → Publish repository.

**Вариант B — сайт github.com (через браузер)**
GitHub принимает не более 100 файлов за раз, поэтому используйте `Amirova_GitHub_web_upload.zip`:
1. github.com → New repository (Public или Private) → «uploading an existing file».
2. Для каждой папки `part1` … `part5` по очереди: открыть папку, выделить ВСЁ внутри (включая папку `media`), перетащить в окно, Commit changes. Папки part1…part5 сами в репозиторий не загружаются — только их содержимое.

## Развёртывание на Vercel
1. vercel.com → Add New → Project → Import Git Repository → выбрать репозиторий.
2. Framework Preset: **Other**. Build Command — пусто. Output Directory — пусто (корень). Root Directory — `./`.
3. Deploy. Сайт будет по адресу `https://<имя>.vercel.app`.
Каждый новый commit в GitHub обновит сайт автоматически.

## Проверка
Открыть `index.html` двойным кликом тоже работает (офлайн). Режим показа: `/#show`, архив: `/#archive`.
