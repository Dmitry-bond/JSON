# HW_GitHub
## JSON

 1. Создать внешний репозиторий c названием JSON.
 2. Клонировать репозиторий JSON на локальный компьютер.
 
	`git clone https://github.com/setter-getter/JSON.git`
 3. Внутри локального JSON создать файл “new.json”
 
	`touch new.json`
 4. Добавить файл под гит.
 
    `git add new.json`
  
 5. Закоммитить файл.
 
	 `git commit -m "add new.json"`
   
 6. Отправить файл на внешний GitHub репозиторий.
 
	 `git push`
    
 7. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.
```
	vim new.json
	i
	
	{
	"first name":"Dmitry",
	"last name":"Bondarenko",
	"patronymic":"Anatolevich",
	"age":"33",
	"number of pets":"1",
	"desired salary":"350"
	}
	
	Esc
	:wq
  ```
  
 8. Отправить изменения на внешний репозиторий.
 ```
	git add new.json
	git commit -m "update new.json"
	git push
 ```
 9. Создать файл preferences.json
 
	`touch preferences.json`
  
 10. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.
```
	vim preferences.json
	i

	{
	"favorite movie":"1=1",
	"TV series":"Frieds",
	"favorite food":"borsch",
	"favorite time of the year":"summer",
	"country I would like to visit":"Iceland"
	}

	Esc
	:wq
```
 11. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON
 ```
	touch sklls.json
	
	vim sklls.json
	i
	
	{
	"skills":{"testing theory":["bug reports","documentation","SDLC","STLC"],
 	"skills of working with":["Git", "bash", "SQL","Fidler","Postman"]}
	}
	
	Esc
	:wq
```
 12. Отправить сразу 2 файла на внешний репозиторий.
 ```
	git add preferences.json sklls.json
	git commit -m "add preferences.json sklls.json"
	git push
 ``` 
 13. На веб интерфейсе создать файл bug_report.json.
 ```
	Add file -> create new file -> bug_report.json
```
 14. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

`	"create bug_report.json" -> commit new file`

 15. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.
	
  `	"Edit this file"`
```
	{
	"ID":"ID",
	"Summary":"Summary",
	"Steps to reproduce": "Steps to reproduce",
	"Actual result":"Actual result",
	"Expected result":"Expected result",
	"Severity":"High",
	"Priority":"Major"
	}
```
 16. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

 ` "update bug_report.json" -> commit changes`

 17. Синхронизировать внешний и локальный репозиторий JSON
 
 `git pull`
