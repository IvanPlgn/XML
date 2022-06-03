	XML

1. Создать внешний репозиторий c названием XML.
repositories - new

2. Клонировать репозиторий XML на локальный компьютер.
git clone ключ ssh

3. Внутри локального XML создать файл “new.xml”.
cd xml
touch new.xml

4. Добавить файл под гит.
git add .

5. Закоммитить файл.
git commit -m "add file new.xml"

6. Отправить файл на внешний GitHub репозиторий.
git push

7. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.
cat >> new.xml
<?xml version="1.0" encoding="UTF-8"?>
	<new>
		<name> Sherloсk </name>
		<surname> Holmes </surname>
		<age>34</age>
		<pets>1</pets>
		<salary>1000000</salary>
	</new>
ctrl + D

8. Отправить изменения на внешний репозиторий.
git commit -am "Add changes file"
git push

9. Создать файл preferences.xml
touch preferences.xml

10. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.
cat >> preferences.xml
<?xml version="1.0" encoding="UTF-8"?>
	<preferences>
		<Favorite movie> RocknRolla </Favorite movie>
		<Favorite TV-show> Top Gir </Favorite TV-show>
		<Favorite food>34</Favorite food>
		<pets> Bolognese </pets>
		<Country to which would like to visit> USA </Country to which would like to visit>
	</preferences>
ctrl + D

11. Создать файл skills.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
cat > skills.xml
<?xml version="1.0" encoding="UTF-8"?>
	<skills>
		<QA> Linux, Git, GitHub, GitBash, API </QA>
	</skills>
ctrl + D

12. Сделать коммит в одну строку.
git add .
git commit -m "Add changes preferences and skills"

13. Отправить сразу 2 файла на внешний репозиторий.
git push

14. На веб интерфейсе создать файл bug_report.xml.
Add file / Create new file

15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
Commit changes "Add new file"

16. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.
Edit this file

17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
Commit changes "Add changes file"

18. Синхронизировать внешний и локальный репозиторий XML
git pull
