1. Создать внешний репозиторий c названием XML.
 - открываем GitHub и создаем репозиторий. Копируем ссылку на репозиторий.
 Repositories->New->Repository name->Public->Add a README file->Create repository
 Repositories->Repository name->Code->Clone

 2. Клонировать репозиторий XML на локальный компьютер.
 - git clone (ссылка не репозиторий). 

 3. Внутри локального XML создать файл “new.xml”.
 - cd XML (заходим в папкe)
 - touch new.xml (создаем файл)

 4. Добавить файл под гит.
 - git add new.xml

 5. Закоммитить файл.
 - git commit -m "add 1 file"

 6. Отправить файл на внешний GitHub репозиторий.
 - git push

 7. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.
 - vim new.xml

<aboutme>
        <name>Inna Gennadyevna Boikova</name>
        <age>28</age>
        <pets>
        <number>1</number>
        <kindofpet>dog</kindofpet>
        <name>Bright</name>
        </pets>
        <Salary>400$</Salary>
 </aboutme>
  
 8. Отправить изменения на внешний репозиторий.
  - git commit -am "change file new.json"
  - git push

 9. Создать файл preferences.xml
 - touch preferences.xml

 10. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.
  - vim preferences.xml

<aboutme>
        <favoritefilm>The Silence of the Lambs</favoritefilm>
        <favoriteseries>Supernatural</favoriteseries>
        <favoritefood>BBQ</favoritefood>
        <favoriteseason>summer</favoriteseason>
        <country>Switzerland</country>
 </aboutme>

 11. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
 - vim sklls.xml

<allskills>
        <skill1>GIT</skill1>
        <skill2>Postman</skill2>
        <skill3>Charles</skill3>
        <skill4>other<skill4>
</allskills>

 12. Сделать коммит в одну строку.
 - git add . | git commit -m "2 files"

 13. Отправить сразу 2 файла на внешний репозиторий.
 - git push

 14. На веб интерфейсе создать файл bug_report.xml.
 - add file
 - create new file 
 - commit new file

 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
  - commit changes

 16. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.
 - edit this file
<bugreport>
	<Identifier>1</Identifier>
  	<Summary>Site layout on the first page is not recommended with layout placement</Summary>
	<Descriprion>Actual result and Expected result</Descriprion>
	<Actual result>The layout of the site on the first page does not match the layout of the application. More than 5 pixel spacing</Actual result>
	<Expected result>The layout of the site on the first page matches the layout when overlaying. Run up to 5 pixels</Expected result>
	<Attachment>https://www.screencast.com/t/hkQkQ8CeueY8</Attachment>
	<Steps to reproduce>
		<step1>Open website in Chrome</step1>
	      	<step2>Install and open PerfectPixel browser plugin</step2>
              	<step3>Drag the layout of the first page of the site in jpg format into the plugin window</step3>
              	<step4>Set the parameters in the plugin x=1, y=1, scale=0.24</step4>
                <step5>Apply a layout layer to the layout of the site according to the edges of the main block</step5>
              	<step6>Hold down Shift + use arrow keys to change position by 10px</step6>
	</Steps to reproduce>
	<Severity>minor</Severity>
	<Priority>low</Priority>
</bugreport>

 17.  Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 - commit changes

 18.  Синхронизировать внешний и локальный репозиторий XML
  - git pull
