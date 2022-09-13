# Что и как рекомендуют делать для работы с [[GitHub]] при работе в [[JntelliJ]].

## При создании нового проекта.
- [ ] Создаем новыый проект
	- [ ] в корне проекта создаем файл '.gitignore'
	- [ ] для него ищем в сети наполнение для '.gitignore' фразой "gitignore global jetbrains" чтобы не отправить в Гит служебную информацию IDE не  относящуюся к программированию непосредственно.
	- [ ] находим [.gitignore](https://github.com/github/gitignore/blob/main/Global/JetBrains.gitignore)
	- [ ] делаем из сети копи и паст в корневой файл проекта '.gitignore'
	- [ ] ниже 'out/' добавляем строку с 'target/'

## Загрузаем проект в GitHub
- [ ] в главном меню 'File / settings'
	- [ ] 'Version control / GitHub' добавляем свой экаунт;
	- [ ] убираем птичку в поле 'Clone git repositories using ssh'
- [ ] В главном меню 'VCS / Share project on GitHub'
- [ ] Remote = main
- [ ] Description = Learning java level 1 with gitHub in GeekBrains.
- [ ] Share