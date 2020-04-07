# internship
1. git config  
служит для указания пользовательских настроек, таких как электронная почта, имя пользователя.
* К примеру, данная команда используется для установки адреса электронной почты:
>git config --global user.email адрес@gmail.com  

2. git init - используется для создания GIT репозитория.
3. git clone - клонирует GIT репозиторий. 
* Если репозиторий находится на удаленном сервере, используется команда такого рода:
>git clone имя.пользователя@хост:/путь/до/репозитория
* И наоборот, для клонирования локального репозитория используйте:
>git clone /путь/до/репозитория

4. git remote - позволяет пользователю подключиться к удаленному репозиторию.
5. git commit - используется для коммита изменений в файлах проекта.(добавляет комментарий).

6. git add 
способствует добавлению файлов в индекс.
К примеру, следующая команда добавит файл под названием temp.txt присутствующий в локальном каталоге в индекс:
* git add temp.txt

git status - отображает список измененных файлов, вместе с файлами, которые еще не были добавлены в индекс или ожидают коммита.
git grep - позволяет проводить поиск фраз и слов .
git checkout - может быть использована для создания веток или переключения между ними.
git branch - используется для отображения, создания или удаления веток(git branch -d).
git show - используется для просмотра информации о любом git объекте
git rm - используется для удаления файлов из индекса и рабочего каталога.
git log - отображает список всех коммитов в ветке вместе с соответствующими сведениями.
git reset - используется для сброса индекса и рабочего каталога до последнего состояния коммита.
git tag - используется для маркировки определенных коммитов с помощью простых меток.
git diff - используется для выявления различий между ветками.
git merge - используется для объединения ветки в активную ветвь.
git pull - используется для объединения изменений, присутствующих в удаленном репозитории, в локальный рабочий каталог.
git push - позволяет поместить изменения в главную ветку удаленного хранилища связанного с рабочим каталогом.
