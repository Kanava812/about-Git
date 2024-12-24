# Что такое Git?
Любой творческий процесс состоит из набора итераций. Художник рисует эскизы, фотограф делает несколько кадров, студент создаёт файлы диплом.doc, диплом_final.doc и диплом_final_final_2.doc. Каждая такая попытка имеет ценность. Она позволяет остановиться и убедиться, что работа идёт в правильном направлении.   
В отличие от художников, разработчики не используют скетчбуки. Историю их проектов хранит отдельная программа — *система контроля версий (англ. Version Control System, или коротко VCS).*   
**Система контроля версий, или VCS** — это программное обеспечение, которое помогает отслеживать изменения в программах, текстовых файлах, больших документах, веб-сайтах и так далее.    
Одно изменение или группу изменений в VCS называют ревизией или версией. Каждая такая ревизия содержит информацию о том, что изменилось, кто внёс изменения, когда это было и иногда комментарии к изменению.   
**Основные функции системы контроля версий:**   
хранит историю изменений в виде отдельных ревизий;   
позволяет манипулировать историей: например, менять порядок ревизий, полностью удалять версии, возвращаться назад в истории;   
помогает анализировать изменения: например, кто и когда вносит изменения, кто чаще всего вносит изменения в определённый файл и так далее.   
Система контроля версий — общее название ряда продуктов, таких как Git, Mercurial, Subversion и других. Самый популярный из них — [Git](На английском сленге слово git означает «мерзавец». Но, по мнению Линуса Торвальдса, создателя Git, это название может расшифровываться как угодно — в зависимости от настроения пользователя.
Например, Global Information Tracker (англ. «глобальный информационный трекер») — когда у вас всё хорошо и Git работает отлично. А если что-то идёт не так, Git превращается в Goddamn Idiotic Truckload of sh*t (англ. «чёртов идиотский грузовик c ...» — тут вы наверняка справитесь с переводом и без нас). ).   
## Навигация
pwd (от англ. print working directory, «показать рабочую папку») — покажи, в какой я папке;   
ls (от англ. list directory contents, «отобразить содержимое директории») — покажи файлы и папки в текущей папке;   
ls -a — покажи также скрытые файлы и папки, названия которых начинаются с символа .;   
cd first-project (от англ. change directory, «сменить директорию») — перейди в папку first-project;   
cd first-project/html — перейди в папку html, которая находится в папке first-project;   
cd .. — перейди на уровень выше, в родительскую папку;   
cd ~ — перейди в домашнюю директорию (/Users/Username);   
cd / — перейди в корневую директорию.   
## Работа с файлами и папками   
### Создание   
touch index.html (англ. touch, «коснуться») — создай файл index.html в текущей папке;   
touch index.html style.css script.js — если нужно создать сразу несколько файлов, можно напечатать их имена в одну строку через пробел;   
mkdir second-project (от англ. make directory, «создать директорию») — создай папку с именем second-project в текущей папке.   
### Копирование и перемещение   
cp file.txt ~/my-dir (от англ. copy, «копировать») — скопируй файл в другое место;   
mv file.txt ~/my-dir (от англ. move, «переместить») — перемести файл или папку в другое место.   
### Чтение   
cat file.txt (от англ. concatenate and print, «объединить и распечатать») — распечатай содержимое текстового файла file.txt.   
### Удаление   
rm about.html (от англ. remove, «удалить») — удали файл about.html;   
rmdir images (от англ. remove directory, «удалить директорию») — удали папку images;   
rm -r second-project (от англ. remove, «удалить» + recursive, «рекурсивный») — удали папку second-project и всё, что она содержит.   
