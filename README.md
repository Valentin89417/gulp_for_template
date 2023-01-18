gulp# Сборка проекта на Gulp 4


## Зупуск:  
1. Скачать все файлы проекта 
2. Перенести файлы шаблона в проект
3. Проверить подключение стилей шаблона в файле /src/css/style.scss - строка 2
4. Заменить в .html путь к стилям assets/css/main.css на assets/css/style.min.css
5. Добавить перед закрывающим body <script src="assets/js/castom.js"></script>
3. В терминале перейти в каталог проекта
4. Выполнить команду: npm i (должен быть установлен [node.js](https://nodejs.org/ru/))  
5. Выполнить команду: gulp (должен быть установлен [gulp](https://gulpjs.com/docs/en/getting-started/quick-start/))  
6. Писать свой код и наслаждаться автоматической сборкой проекта. 

## Перенос файлов из шаблона в проект
|| HTML | Styles | Scripts | Images | Source |
|:---|:------:|:-----:|:----:|:-----:|:-----:|
| **Шаблон** | /*.html | assets/css/* | assets/js/ | assets/img/ | assets/vendor/ |
| **Проект** | /*.html | src/css/* | src/js/ | src/img/ | src/vendor/ |



## Используемые NPM пакеты
[gulp](https://www.npmjs.com/package/gulp) Сборщик Gulp  
[gulp-less](https://www.npmjs.com/package/gulp-less) Компиляция Less файлов  
[sass](https://www.npmjs.com/package/sass) Компилятор Sass  
[gulp-sass](https://www.npmjs.com/package/gulp-sass) Компиляция Sass и Scss файлов  
[gulp-uglify](https://www.npmjs.com/package/gulp-uglify) Сжатие и оптимизация Java Script кода  
[gulp-babel](https://www.npmjs.com/package/gulp-babel) Преобразует Java Script в старый стандарт  
[@babel/core](https://www.npmjs.com/package/@babel/core) Ядро Babel  
[@babel/preset-env](https://www.npmjs.com/package/@babel/preset-env) Пресет для компиляции Babel  
[gulp-clean-css](https://www.npmjs.com/package/gulp-clean-css) Минификация и оптимизация CSS файлов   
[del](https://www.npmjs.com/package/del) Удаление каталогов и файлов  
[gulp-sourcemaps](https://www.npmjs.com/package/gulp-sourcemaps) Карта строк кода для инструментов  разработчика   
[gulp-autoprefixer](https://www.npmjs.com/package/gulp-autoprefixer) Автоматическое добавление префиксов в CSS   
[gulp-imagemin](https://www.npmjs.com/package/gulp-imagemin) Сжатие изображений   
[gulp-concat](https://www.npmjs.com/package/gulp-concat) Объединение нескольких файлов в один  
[gulp-newer](https://www.npmjs.com/package/gulp-newer) Отслеживание только новых файлов  
[gulp-rename](https://www.npmjs.com/package/gulp-rename) Переименовывает файлы    
[gulp-size](https://www.npmjs.com/package/gulp-size) Отображение информации о размерах файлов в терминале  


### Контакты
[![Telegram](https://img.shields.io/badge/-Telegram-333?style=for-the-badge&logo=telegram&logoColor=27A0D9)](https://t.me/kv89417)
[![VK](https://img.shields.io/badge/-VK-333?style=for-the-badge&logo=Vk&logoColor=27A0D9)](https://vk.com/valentin_tin_tin)
[![GitHub](https://img.shields.io/badge/-GitHub-333?style=for-the-badge&logo=GitHub&logoColor=fff)](https://github.com/Valentin89417)
