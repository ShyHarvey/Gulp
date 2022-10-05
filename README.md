## Input
|| HTML | Styles | Scripts | Images |
|:---|:------:|:-----:|:----:|:-----:|
| **Каталог** | src/ | src/styles/ | src/scripts/ | src/img/ |
| **Расширение** | .html, .pug | .css, .sass, .scss, .less, .styl | .js, .ts, .coffee | .jpg, .png, .gif |

## Output
|| HTML | CSS | JavaScript | Images |
|:---|:------:|:-----:|:----:|:-----:|
| **Путь** | dist/ | dist/css/style.min.css | dist/js/main.min.js | dist/img/ |


## Функционал сборки
- компиляция препроцессора PUG
- минификация HTML
- компиляция препроцессоров LESS, SASS, STYLUS
- минификация CSS
- автоматическое добавление префиксов CSS
- транспиляция языков Type Script и Coffee Script
- преобразования кода ECMAScript 2015 + в обратно совместимую версию JavaScript с помощью Babel
- минификация JavaScript
- объединение нескольких файлов JavaScript в один
- сжатие изображений
- отслеживание новых изображений, которые еще не были сжаты
- отслеживание изменений в файлах и автоматический запуск повторной обработки
- генерация sourcemaps
- отображение размеров файлов в терминале
- локальный сервер с автоматическим обновлением страницы при изменении файлов
