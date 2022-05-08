# JSON_HW
 4. Создать внешний репозиторий c названием JSON.
New - имя репозитории JSON - галочка (файл readme)- ok

 5. Клонировать репозиторий JSON на локальный компьютер.
git clone https://github.com/marinaV32/JSON.git (ссылка из репозитории раздел https)
 
6. Внутри локального JSON создать файл “new.json”.
touch new.json

 
7. Добавить файл под гит.
git add new.json
 
8. Закоммитить файл.
git commit -m "my new"
 
9. Отправить файл на внешний GitHub репозиторий.
git push
 
10. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.
vim new.json 
жмем а на клавиатуре (команда дляя записи текста в редакторе)
(пишем текст внутри)

       {   "full name":"Prokopovich Marina", 
          "age":"26",
          "number of pets":"no",
          "future desired salary":"2000$" }
жмем Esc и  :wq(сохранить и выйти)
         
11. Отправить изменения на внешний репозиторий.
git commit -am "filled"
git push
 
12. Создать файл preferences.json
vim preferences.json (создаем и сразу редактируем)
либо touch preferences.json

 13. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.
vim preferences.json
жмем а на клавиатуре (команда дляя записи текста в редакторе)
(пишем текст внутри)
{ "favorite movie":"oath",
    "favorite series":"from outside",
    "favorite food":"pasta",
    "favorite season":"spring",
    "travel country":"Greece" }
жмем Esc и  :wq(сохранить и выйти)
         
14. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON
vim sklls.json
жмем а на клавиатуре (команда дляя записи текста в редакторе)
(пишем текст внутри)
 { "course qa":"hard skills,soft skills" }
жмем Esc и  :wq(сохранить и выйти)
 
15. Отправить сразу 2 файла на внешний репозиторий.
git add .
git commit -m "to fa"
git push
 
16. На веб интерфейсе создать файл bug_report.json. 
В Гите заходим на наш репозиторий JSON, жмем "Создать новый файл", даем имя файлу - сохраняем

17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 18. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON. 
В репозитории находим нужный файл, жмем на редактирование (карандаш справа) и вводим текст

{ "Name":"structure bug report",
"Issue Title":"Pop-up window does not disappear until the date is not changed",
"Issue Type":"Bug",
"Priority":"Low",
"Issue Status":"Blocked",
"Author(Created by)":"Marina Prokopovich",
"Severity":" ",
"Build":" ",
"Environment":" ", 
"Name2":"Issue Description, Steps to reproduce",
"step1":"Select any dish",
"step2":"Go to the basket",
"step3":"Select a date next to the last delivery date in the menu(e.x. menu 8-11 Nov, select 15 Nov)",
"step4":"After the pop-up 'Delivery up t 14.11'appears click on the 'Change a date' button",
"step5":"Look at the pop-up",

"t1" = "Expected result:The pop-up 'Delivery up to 14.11' does not appear",
"t2" = "Actual result:The Pop-up remains until the date is not changed to the suitable one" }

Жмем сохранить и переходим в кансоль чтобы синхронизровать наши изменния с локальным и внешним репозиториями.
 
19. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 20. Синхронизировать внешний и локальный репозиторий JSON
+++++на 17-20: создала новый файл в репозитории, затем через консоль гид синхронизировала с локальным и внешним репозиторием: 
git fetch   проверила
git pull    синхронизировала
Редактировала: добавила текст 
git fetch   
git pull
