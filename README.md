# Tiny Site — GitHub Pages
Готовый минимальный статический сайт (HTML/CSS/JS + одна картинка).

## Быстрый старт (через веб-интерфейс)
1. Откройте https://github.com/new и создайте репозиторий, например **tiny-site**.
2. Загрузите все файлы из этого проекта в корень репозитория.
3. В репозитории перейдите в **Settings → Pages**.
4. В блоке **Build and deployment** выберите:
   - **Source**: *Deploy from a branch*
   - **Branch**: *main* (или *master*) и **/ (root)**
5. Нажмите **Save**. Через минуту сайт будет доступен по адресу:
   `https://<ваш-логин>.github.io/<имя-репозитория>/`

## Быстрый старт (через Git)
```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/<user>/<repo>.git
git push -u origin main
```
Дальше включите Pages: *Settings → Pages* → *Deploy from a branch*.

## Кастомизация
- Текст — редактируйте **index.html**.
- Стили — **style.css**.
- Картинка — **assets/cover.svg** (можно заменить PNG/JPG и поправить `src`).
- JS — **script.js**.

## Примечания
- Файл **.nojekyll** отключает Jekyll, чтобы GitHub Pages отдавал статические файлы как есть.
