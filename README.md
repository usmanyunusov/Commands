# <h1>Полезные команды для работы с Git</h1>

<ul>
	<li>git add <filename> <filename> — индексация определенных файлов (можно перечислять)</li>
	<li>git add . — добавление всех файлов в git для отслеживания</li> 
	<li>git rm <filename> <filename> — удаляет файлы по их имени из репозиторий</li>
	<li>git clean -f -d — удаляет весь мусор и неотслеживаемые файлы</li>
	<li>git branch new_feature — создает новую ветку</li>
	<li>git checkout new_feature — переход на нужную ветку</li>
	<li>git commit -a — делаем коммит всех изменений в new_feature</li>
	<li>git checkout master — переключаемся на master</li>
	<li>git merge new_feature — мерджим ветку new_feature</li>
	<li>git branch — получаем список веток</li>
	<li>git branch -d some_branch — удалить ветку</li>
	<li>git reset --hard d8578ed — откатиться к конкретному коммиту (хэш смотрим в «git log»)</li>
	<li>git clean -f — удаление untracked files:</li>
	<li>git log, gitk — просмотр истории коммитов</li>
	<li>git rm --cached path_to_file — удаление файлов из индекса</li>
</ul>


 