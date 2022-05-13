 Как отправить ДЗ на проверку.
 1. Создайте текстовый файл как в первом ДЗ по Terminal.
 2. Сценарий перенесите в этот файл.
 3. На против каждого действия - напишите команду в GitBash

***JSON***

 4. ***Создать внешний репозиторий c названием JSON.*** === **``https://github.com/victut?tab=repositories -> New -> Repository name "JSON" -> Create repository``**
 5. ***Клонировать репозиторий JSON на локальный компьютер.*** === **``git clone https://github.com/victut/JSON.git``**
 6. ***Внутри локального JSON создать файл “new.json”.*** === **``cd JSON/ -> vim new.json -> esc -> :wq -> enter``**  
 7. ***Добавить файл под гит.*** === **``git add new.json``**
 8. ***Закоммитить файл.*** === **``git commit -m "Create new.json"``**
 9. ***Отправить файл на внешний GitHub репозиторий.*** === **``git push``**
 10. ***Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.*** === **``vim new.json``** ->  
	
	{"firstName" : "Victoria",
	"lastName": "Tutaeva",
	"patronymic" : "Vasilevna",
	"age" : 33,
	"pet" : 0,
	"futureDesiredSalary" : "1500$"}
 
 **``-> esc -> :wq -> enter``**
 
 11. ***Отправить изменения на внешний репозиторий.*** === **``git commit -am "modified new.json" -> git push``**
 12. ***Создать файл preferences.json**** === **``vim preferences.json``** 
 13. ***В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.*** ===

	{"favoriteMovie" : "Lord of the Rings",
	"favoriteSeries" : "Suits",
	"favoriteFood" : "ice cream",
	"favoriteSeason" : "Spring",
	"countryYouWouldLikeToVisit" : "USA"}

 **``-> esc -> :wq -> enter``**
 
 14. ***Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON*** === **``vim sklls.json``** ->

	{"skills" : ["Git", "JavaScript", "SQL", "API", "testing theory" ]}

**``-> esc -> :wq -> enter``**

 15. ***Отправить сразу 2 файла на внешний репозиторий.*** === **``git add . -> git commit -m "Created preferences.json, sklls.json" ->  git push``**
 16. ***На веб интерфейсе создать файл bug_report.json.*** === **``add file (https://github.com/victut/JSON) -> Create new file -> JSON/bug_report.json``**
 17. ***Сделать Commit changes (сохранить) изменения на веб интерфейсе.*** === **``commit new file``**
 18. ***На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.*** === **``"edit this file" https://github.com/victut/JSON/blob/main/bug_report.json``** -> 

	{"ID" : 1,
	"Summary" : "When clicking on the 'Update' button, the product is not added to the minicart from the product page", 
	"StepToReproduce" : "Open the website page: http://astrio-spa.dev-mage3.com/venia-accessories.html Open the product card. Add item to cart",
	"Result" : "A pop-up window does NOT appear stating that the item has been added to the cart. The cart counter has NOT increased by the number of items added 	to the cart. There is no item in the cart",
	"ExpectedResult" : "A pop-up window appears stating that the product has been added to the cart. The cart counter has increased by the number of items added to 	the cart. The item has been added to the cart",
	"Reproducibility" : "Not on all product pages",
	"Severity" : "Critical",
	"Priority" : "High(1)",
	"Environment" : "Windows 7 x64 Google Chrome Version 96.0.4664.45, (64 bit)"}

 19. ***Сделать Commit changes (сохранить) изменения на веб интерфейсе.*** === **``Commit changes``**
 20. ***Синхронизировать внешний и локальный репозиторий JS*** === **``git pull``**

***XML***

 21. ***Создать внешний репозиторий c названием XML.*** === **``https://github.com/victut?tab=repositories -> New -> Repository name "XML" -> Create repository``**
 22. ***Клонировать репозиторий XML на локальный компьютер.*** === **``git clone https://github.com/victut/XML.git``**
 23. ***Внутри локального XML создать файл “new.xml”.*** === **``cd XML/ ->  vim new.xml -> esc -> :wq -> enter``**
 24. ***Добавить файл под гит.*** === **``git add new.xml``**
 25. ***Закоммитить файл.*** ===  **``git commit -m "Created new.xml"``**
 26. ***Отправить файл на внешний GitHub репозиторий.*** === **``git push``**
 27. ***Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.*** === **``vim new.xml``** ->

	<?xml version="1.0" encoding="windows-1251"?>
	<personal information>
	   <first name>Victoria</first name>
	   <last name>Tutaeva</last name>
	   <patronymic>Vasilevna</patronymic>
	   <age>33</age>
	   <pet>0</pet>
	   <future desired salary>1500$</future desired salary>
        </personal information>

**``esc -> :wq -> enter``**

 28. ***Отправить изменения на внешний репозиторий.*** === **``git commit -am "modified new.xml" -> git push``**
 29. ***Создать файл preferences.xml*** === **``vim preferences.xml``**
 30. ***В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.*** ===

	<?xml version="1.0" encoding="windows-1251"?>
	<preferences>
	   <favorite movie>Lord of the Rings</favorite movie>
	   <favorite series>Suits</favorite series>
	   <favorite food>ice cream</favorite food>
	   <favorite season>Spring</favorite season>
	   <country you would like to visit>USA</country you would like to visit>
        </preferences>

**``-> esc -> :wq -> enter``**

 31. ***Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML*** === **``vim sklls.xml``** -> 

	<?xml version="1.0" encoding="windows-1251"?>
	<skills>Git, JavaScript, SQL, API, testing theory</skills>
	
**``-> esc -> :wq -> enter``**	

 32. ***Сделать коммит в одну строку.*** === **``git commit -am "modified prefereces.xml, sklls.xml"``**
 33. ***Отправить сразу 2 файла на внешний репозиторий.*** === **``git push``**
 34. ***На веб интерфейсе создать файл bug_report.xml.*** === **``add file (https://github.com/victut/XML) -> Create new file -> XML/bug_report.xml``**
 35. ***Сделать Commit changes (сохранить) изменения на веб интерфейсе.*** === **``commit new file``**
 36. ***На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.*** === **``"edit this file" https://github.com/victut/XML/edit/main/bug_report.xml``** ->

	<?xml version="1.0" encoding="windows-1251"?>
	<bug report>
	   <ID>1</ID>
	   <Summary>When clicking on the 'Update' button, the product is not added to the minicart from the product page</Summary>
	   <StepToReproduce>Open the website page: http://astrio-spa.dev-mage3.com/venia-accessories.html Open the product card. Add item to cart</StepToReproduce>
	   <Result>A pop-up window does NOT appear stating that the item has been added to the cart. The cart counter has NOT increased by the number of items added to 	the cart. There is no item in the cart</Result>
	   <ExpectedResult>A pop-up window appears stating that the product has been added to the cart. The cart counter has increased by the number of items added to the cart. The item has been added to the cart</ExpectedResult>
	   <Reproducibility>Not on all product pages</Reproducibility>
	   <Severity>Critical</Severity>
	   <Priority>High(1)</Priority>
	   <Environment>Windows 7 x64 Google Chrome Version 96.0.4664.45, (64 bit)</Environment>
        </bug report>	   

 37. ***Сделать Commit changes (сохранить) изменения на веб интерфейсе.*** === **``Commit changes``**
 38. ***Синхронизировать внешний и локальный репозиторий XML*** === **``git pull``**





