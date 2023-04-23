<div align="center">

# Git Homework 2 "XML"

</div> 

 21. Создать внешний репозиторий c названием XML.  
 `https://github.com/mranolegprivate/XML`
 22. Клонировать репозиторий XML на локальный компьютер.  
 `git clone git@github.com:mranolegprivate/XML.git`
 23. Внутри локального XML создать файл “new.xml”.  
 `touch new.xml`
 24. Добавить файл под гит.  
 `git add .`
 25. Закоммитить файл.  
 `git commit -m 'first commit XML'`
 26. Отправить файл на внешний GitHub репозиторий.  
 `git push`
 27. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.  
 `vim new.xml`
 ```XML
 <root>
   <name>An Oleg Romanovich</name>
   <age>35</age>
   <animal>2</animal>
   <salary>5000$</salary>
 </root>
 ```
 28. Отправить изменения на внешний репозиторий.  
 `git add .`
 `git commit -m 'secont commit XML'`
 `git push`
 29. Создать файл preferences.xml  
 `touch preferences.xml`
 30. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.  
 `vim preferences.xml`
 ```xml
 <root>
   <favorite_movie>Avatar</favorite_movie>
   <favorite_series>The Mandalorian</favorite_series>
   <favorite_food>Sangepsal</favorite_food>
   <favorite_season>summer</favorite_season>
   <country_to_travel>Singapore</country_to_travel>
 </root>
 ```
 31. Создать файл skills.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML  
 `vim skills.xml`
 ```xml
 <root>
  <terminal>Git Linux Terminal<terminal>
  <theory>Testing Theory</theory>
  <server>Client server</server>
  <sql>SQL</sql>
  <api>Postman</api>
  <traf>Charles Fiddler Sniffing<traf>
  <web>Web Services</web>
  <DevTools>DevTools</DevTools>
  <mobile>Mobile Testing</mobile>
  <webTesting>Web Testing</webTesting>
  <load>Load testing</load>
 </root>
 ```
 32. Сделать коммит в одну строку.  
 `git commit -am 'commit XML'`
 33. Отправить сразу 2 файла на внешний репозиторий.  
 `git push`
 34. На веб интерфейсе создать файл bug_report.xml.  
 В репозитории нажать  `Add file` далее `Create new file` в поле "Name your file..." ввести `bug_report.xml`
 35. Сделать Commit changes (сохранить) изменения на веб интерфейсе.  
 Нажать кнопку `[Commit new file]`
 36. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.  
 ```xml
<root>
 <ID>HW-2x</ID>
 <Title>What?Where?When?</Title>
 <Severity>Medium</Severity>
 <Priority>High</Priority>
 <Precondition>Preparation steps</Precondition>
 <Environment>Devices</Environment>
 <STR>Steps to restore</STR>
 <ER>Expected result</ER>
 <AR>Actual Result</AR>
 <Attachment>link</Attachment>
 </root>
```
 37. Сделать Commit changes (сохранить) изменения на веб интерфейсе.  
 Нажать кнопку `[Commit changes]`
 38. Синхронизировать внешний и локальный репозиторий XML.  
`git pull`
