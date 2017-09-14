# <h1>Полезные команды для работы с Git</h1>

<ul>
	<li><b>git init</b> — инициалиализация git</li>
	<li><b>git add filename filename</b> — добавление отдельных файлов для отслеживания (можно перечислять)</li>
	<li><b>git add .</b> — добавление всех файлов в git для отслеживания</li> 
	<li><b>git rm filename filename</b> — удаляет файлы по их имени из репозиторий</li>
	<li><b>git clean -f -d</b> — удаляет весь мусор и неотслеживаемые файлы</li>
	<li><b>git branch new_feature</b> — создает новую ветку</li>
	<li><b>git checkout new_feature</b> — переход на нужную ветку</li>
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
</ul>


 
