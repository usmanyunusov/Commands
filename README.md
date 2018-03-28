# Полезные команды
[Начало работы с Git](#Начало-работы-с-git) <br>
[Полезные команды для работы с Git](#Команды-для-работы-с-git) <br>
[Полезные команды для работы с Bash](#Команды-для-работы-с-bash)
## Начало работы с Git
<b>Git</b> — мощная и сложная распределенная система контроля версий. Понимание всех возможностей git открывает для разработчика новые горизонты в управлении исходным кодом. Самый верный способ обучиться владению Git — испытать его своими руками.

## Команды для работы с Git

<ul>
	<li><b>git init</b> — инициалиализация git</li>
	<li><b>git add filename filename</b> — добавление отдельных файлов для отслеживания (можно перечислять)</li>
	<li><b>git add .</b> — добавление всех файлов в git для отслеживания</li> 
	<li><b>git rm filename filename</b> — удаляет файлы по их имени из репозиторий</li>
	<li><b>git clean -f -d</b> — удаляет весь мусор и неотслеживаемые файлы</li>
	<li><b>git branch new_feature</b> — создает новую ветку</li>
	<li><b>git checkout new_feature</b> — переход на нужную ветку</li>
	<li><b>git checkout -b new_feature</b> — создает новую ветку и переходит на эту ветку</li>
	<li><b>git commit -a</b> — делаем коммит всех изменений в new_feature</li>
	<li><b>git checkout master</b> — переключаемся на master</li>
	<li><b>git merge new_feature</b> — мерджим ветку new_feature</li>
	<li><b>git branch</b> — получаем список веток</li>
	<li><b>git branch -d some_branch</b> — удалить ветку</li>
	<li><b>git reset --hard d8578ed</b> — откатиться к конкретному коммиту (хэш смотрим в «git log»)</li>
	<li><b>git clean -f</b> — удаление untracked files:</li>
	<li><b>git log, gitk</b> — просмотр истории коммитов</li>
	<li><b>git rm --cached path_to_file</b> — удаление файлов из индекса</li>
	<li><b>git revert HEAD --no-edit</b> — отмена последнего коммита</li>
	<li><b>git reset HEAD filename</b> — удалить из индексации<sup>?<sup></li>
	<li><b>git checkout filename</b> — убрать из индексации файла <sup>?<sup></li>
	<li><b>git log --decorate --graph --all --oneline</b> — просмотр истории коммитов в графическом виде</li>
	<li><b>git log</b> — просмотр истории коммитов в git</li>
	<li><b>git fetch repos [repos - имя удал. сервера]</b> — получение изменений на удаленном сервере</li>
	<li><b>git branch -d branch_name [branch_name - имя ветки]</b> — удаление ветки в git</li>
	<li><b>git reset --hard origin/master</b> — оптимизирует ветку master</li>
	<li><b>git pull origin "ветка"</b> — стягивает все измененияиз оригинала</li> 
	<li><b>git rm -f file1 file2 ... fileN</b> — удалить файл из комита и с жесткого диска</li>
	<li><b>git reset --hard</b> — отменить все изменения, сделанныe в дереве, до состояния, которое было при последнем commit в локальный репозиторий</li>
	<li><b>git reset - EDITEDFILE</b> — удалить из индекса конкретный файл</li>
	<li><b>git reset --hard HEAD~3</b> — навсегда удалить три последних коммита</li>
	<li><b>git revert cgsjd2h</b> — отменить коммит</li>
	<li><b>git fetch --all</b> — загрузит с сервера все изменения, которых у вас еще нет</li>
	<li><b>git mergetool</b> — предоставляет удобный интерфейс для разрешения конфликтов</li>
	<li><b>git stash</b> — временно спрятать изменения, но не фиксировать их</li>	
	<li><b>git stash pop</b> — вернуть спрятанные изменения</li>
	<li><b>ssh-keygen</b> — генерировать ssh-ключи</li>
	<li><b>git checkout -b <название ветки> origin/<название ветки></b> — получить удаленную ветку (branch)</li>
</ul>

## Команды для работы с Bash

<ul>
	<li>Ну начнем</li>
</ul>
 

 
