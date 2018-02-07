# Gulp сборка для совместной работы

Данный стартовый шаблон имеет gulp задачи:
 - browser-sync - локальный сервер;
 - gulp-less и gulp-pug для компиляции less, pug файлов;
 - gulp-sourcemaps создания карт стилей;
 - autoprefixer для автоматического проставления префиксов;
 - gulp-notify для нотификации ошибок;
 - gulp-plumber для того чтобы не перезапускать gulp если была допущена ошибка;
 - del для удаления файлов перед копированием;
 - run-sequence для последовательного запуска наших тасков;
 - gulp-watch чтобы отслеживать наши изменения в файлах;
 - gulp-svgmin, gulp-cheerio, gulp-replace, gulp-svgsprite для работы с svg;
 - gulp-rename для переименование файлов;
 - gulp-imagemin, imagemin-pngquant для оптимизации изображений;
 - gulp-usemin, gulp-htmlclean, gulp-uglify, gulp-minify-css, gulp-rev для оптимизации html, css, js файлов.
   
### С чего начать:

1. Перед клонировнием убедитесь, что путь до папки с проектом не будет содержать кириллицы (только латиница).
2. Клонируйте свой форк к себе локально, перейдите в ветку develop если вы еще не в ней.
3. Из ветки develop создайте свою ветку название которой будет соответствовать названию вашему заданию.
4. После выполнения задания, сделайте pull request тимлидеру на проверку.

### Как запустить проект

Установить npm пакеты:

```
npm i
```


Запустить сборку:

```
gulp
```
