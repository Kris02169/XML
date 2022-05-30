# XML
 21. Создать внешний репозиторий c названием XML.
#Open github

#Repositories-New-XML-Create repository
 
 22. Клонировать репозиторий XML на локальный компьютер.
#Open XML-Code- Copy
#Open gitbash

git clone https://github.com/Kris02169/XML.git

 23. Внутри локального XML создать файл “new.xml”.
cd XML
touch new.xml 

 24. Добавить файл под гит.
add new.xml

 25. Закоммитить файл.
git commit -m "New file"

 26. Отправить файл на внешний GitHub репозиторий.
git push

 27. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.
cat >> new.xml
<Name> Kristina </Name>
<Age> 26 </Age>
<Pets> 0 </Pets>
<Salary> 500 </Salary>
ctrl+c

 28. Отправить изменения на внешний репозиторий.
git add new.xml; git commit -m "Update"; git push

  29. Создать файл preferences.xml
cat > preferences.xml

 30. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.
cat >> preferences.xml
<Movie> Meet Joe Black: Sooner or Later Everyone Does </Movie>
<Serial> How a need your mother </Serial>
<Food> Cake </Food>
<Season> Summer </Season>
ctrl+c

 31. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
cat > skills.xml
<Skills> 
	<item0>1. Базовая теория (Что такое тестирование, багрепорты, документация, виды, методы, направления тестирования и т.п.) SDLC, STLC.</item0>
	<item1>2. Что такое клиент-серверная архитектура.</item1>
	<item2>3. HTTP Методы запросов на сервер.</item2>
	<item3>4. Коды ответов HTTP сервера.</item3>
	<item4>5. Структуры HTTP запросов и ответов.</item4>
	<item5>6. Что такое JSON, XML. Их структура.</item5>
	<item6>7. Тестирование API через Postman (JS, автотесты API).</item6>
	<item7>8. Снятие и чтение логов c внешнего сервера.</item7>
	<item8>9. Снифинг http web трафика через Charles и Fiddler.</item8>
	<item9>10. Dev Tools веб браузеров (Google Chrome, FireFox).</item9>
	<item10>11. VPN. (Как работает, зачем нужен, как использовать, варианты инструментов)</item10>
	<item11>12. Мобильное тестирование.</item11>
	<item12>13. Особенность iOS, Android, гайдлайны.</item12>
	<item13>14. Сборка iOS приложений на XCode. (У кого нет Mac компьютера, просто посмотрят)</item13>
	<item14>15. Сборка Android приложений на Android Studio.</item14>
	<item15>16. ADB (управление андройд девайсами).</item15>
	<item16>17. Настройка прокси и vpn на iOS и Android.</item16>
	<item17>18. Перехват (сниффинг) мобильного трафика через Charles и Fiddler на iOS и Android.</item17>
	<item18>19. Командная строка (terminal) Linux (копирование, создание, просмотр, перемещение файлов на серверах без графического интерфейса)</item18>
	<item19>20. Основы bash скриптинг, автоматизация рутинных задач на сервере.</item19>
	<item20>21. Доступ к удалённым серверам.</item20>
	<item21>22. Основы SQL (Create, Delete, Drop, Insert Into, Select, From, Where, Join).</item21>
	<item22>23. База данных Postgres (установка, настройка и использование).</item22>
	<item23>24. Нереляционная база данных Redis (установка, настройка и использование).</item23>
	<item24>25. Нагрузочное тестирование в Jmeter.</item24>
	<item25>26. Методология разработки Scrum</item25>
</Skills>
ctrl+c

 32. Сделать коммит в одну строку.
git add .; git commit -m "New files"

 33. Отправить сразу 2 файла на внешний репозиторий.
git push

 

 34. На веб интерфейсе создать файл bug_report.xml.
#Add file -Create new file - bug_report.xml

 35. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
#Commit new file

 36. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.
#bug_report.json-edit this file

<Bug_id> 1 </Bug_id> 
<Title> The "pay" button is missing
<Severity> major </Severity>
<Priority> high </Priority>
<Precondition>
<item1> 1.Payment page. </item1>
<item2> 2.Platform and device don't matter.<item2>
</Precondition>
<Step to reproduce>
<item3> 1.Log in </item3>
<item4> 2.Add item to cart.</item4>
<item5> 3.Click the pay button.</item5>
</Step to reproduce>
<AR> The "pay" button is missing. </AR>
<ER> You can click on "pay" button.</ER> 
<Attachments> https://drive.google.com/file/ </Attachments>
ctrl+c

 37. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
#Commit canges

  38. Синхронизировать внешний и локальный репозиторий XML
git pull
