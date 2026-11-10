# День цифровизации

Небольшой адаптивный сайт с программой и интерактивной викториной. Проект не требует сборки: достаточно открыть `index.html` в браузере.

## Публикация на GitHub Pages

1. Создайте новый публичный репозиторий на GitHub.
2. Загрузите в него `index.html` и этот `README.md`.
3. Откройте **Settings → Pages**.
4. В разделе **Build and deployment** выберите **Deploy from a branch**, ветку `main` и папку `/ (root)`, затем нажмите **Save**.
5. После публикации сайт появится по адресу `https://<ваш-логин>.github.io/<имя-репозитория>/`.

Для загрузки файлов через терминал из папки проекта:

```bash
git init
git add index.html README.md
git commit -m "Add Day of Digitalization site"
git branch -M main
git remote add origin https://github.com/<ваш-логин>/<имя-репозитория>.git
git push -u origin main
```

Шрифт и фоновое фото загружаются из внешних источников, поэтому для их отображения требуется подключение к интернету.