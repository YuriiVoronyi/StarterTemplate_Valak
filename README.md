ВАЖНО: перед запуском этого сборщика у вас должны быть установлены на компьютере:
а. node.js
   сайт для установки node.js
   https://nodejs.org/en/download/prebuilt-installer
b. gulp
   инструкция - команда и описание по установке gulp (команда: npm install --global gulp-cli) на этом сайте:
   https://gulpjs.com/docs/en/getting-started/quick-start

Далее по списку:
1. В Папке PROJ делаем клон репозитория командой в терминале редактора VSCode: git clone git@github.com:YuriiVoronyi/StarterTemplate_Valak.git 
2. В результате клонирования, в папке PROJ появится подпапка StarterTemplate_Valak, в которой будет склонированный репозиторий.
3. Переносим содержимое подпапки StarterTemplate_Valak на уровень выше - в папку PROJ. Если не будем пушить изменения на гитхаб, то не переносим
скрытую папку .git и файл README.md
4. Подпапку StarterTemplate_Valak удаляем.
5. В VSCode открываем папку PROJ, и набираем команду npm install
6. В результате появится папка node_modules и файл package-lock.json
7. Проект запускаем командой gulp watch
8. В результате откроется браузер отображающий содержимое файла index.html из папки src