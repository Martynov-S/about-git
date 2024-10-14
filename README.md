# Шпаргалка по Git


###Git - система контроля версий


Система контроля версий — это программное обеспечение, которое помогает отслеживать изменения в программах, текстовых файлах, больших документах, веб-сайтах и так далее. 


Основные функции системы контроля версий:
- хранит историю изменений в виде отдельных ревизий;
- позволяет манипулировать историей: например, менять порядок ревизий, полностью удалять версии, возвращаться назад в истории;
- помогает анализировать изменения: например, кто и когда вносит изменения, кто чаще всего вносит изменения в определённый файл и так далее.


В каких случаях стоит использовать Git?

- Для синхронизации изменений, сделанных разными участниками команды.
- Чтобы хранить историю изменений файлов при командной работе.
- Для хранения нескольких версий проекта, над которым работает один человек.


Основные команды Git.

**git init**  
Чтобы Git начал отслеживать изменения в проекте, папку с файлами этого проекта нужно сделать **Git-репозиторием**.  
Для этого следует переместиться в неё и ввести команду git init


**git status**  
Проверить статус, или состояние, репозитория поможет команда git status.


**git add**  
Добавляет в репозиторий файлы.  
git add <имя_файла> *один файл*  
git add --all *все файлы*  
git add . *всю текущую папку*


**git commit**  
Выполнить коммит.  
git commit -m 'описание коммита'


**git log**
Просмотреть историю коммитов.  
git log


**git remote add**
Привязать удалённый репозиторий к локальному.
git remote add <имя удалённого репозитория - origin> <его URL - скопировать со страницы удалённого репозитория>  
Убедиться, что репозитории связаны поможет команда git remote -v


**git push**
Отправить изменения на удалённый репозиторий.  
В первый раз эту команду нужно вызвать с флагом -u и параметрами origin (имя удалённого репозитория) и main или master (название текущей ветки).  
Флаг -u свяжет локальную ветку с одноимённой удалённой.





