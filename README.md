# Сборка для вёрстки

Сборка работает с pug/scss/js кодом

### Команды:
* npm i — установка зависимостей 
* npm run dev — запуск локального сервера и вотчеров для сборки css, htmtl и js-бандлов
* npm run build — финальная сборка проекта с минификацией скриптов

### Настройки
Исходные файлы js/scss/pug находятся в директории src, cкомпилированные в build. Пути исходных js файлов можно менять в файле webpack.config, остальные пути лежат в gulpfile.js 
