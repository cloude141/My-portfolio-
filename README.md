# Ugly_322 — лендинг

Одностраничный сайт (вайб-кодер, сайты на заказ). Один файл `index.html`, без сборки и зависимостей (шрифты подгружаются с Google Fonts).

## Как выложить на GitHub Pages

1. Создай репозиторий на GitHub (например `ugly322`).
2. Загрузи файлы `index.html`, `.nojekyll`, `README.md` в корень репозитория (кнопка **Add file → Upload files**), либо через git:
   ```bash
   git init
   git add .
   git commit -m "Landing"
   git branch -M main
   git remote add origin https://github.com/<твой-ник>/<репозиторий>.git
   git push -u origin main
   ```
3. В репозитории открой **Settings → Pages**.
4. В разделе **Build and deployment** выбери **Source: Deploy from a branch**, ветка **main**, папка **/ (root)**, нажми **Save**.
5. Через 1–2 минуты сайт будет доступен по адресу `https://<твой-ник>.github.io/<репозиторий>/`.

Если назвать репозиторий `<твой-ник>.github.io`, сайт откроется прямо по `https://<твой-ник>.github.io/`.
