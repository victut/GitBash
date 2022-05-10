***GitHub. HW_3***

1. ***На локальном репозитории сделать ветки для:***
- ***Postman*** === **``git branch Postman``**
- ***Jmeter*** === **``git branch Jmeter``**
- ***CheckLists*** === **``git branch CheckLists``**
- ***Bug Reports*** === **``git branch Bug_Reports``**
- ***SQL*** === **``git branch SQL``**
- ***Charles*** === **``git branch Charles``**
- ***Mobile testing*** === **``git branch Mobile_testing``**

2. ***Запушить все ветки на внешний репозиторий:***
- ***Postman*** === **``git push -u origin Postman``**
- ***Jmeter*** === **``git push -u origin Jmeter``**
- ***CheckLists*** === **``git push -u origin CheckLists``**
- ***Bug Reports*** === **``git push -u origin Bug_Reports``**
- ***SQL*** === **``git push -u origin SQL``**
- ***Charles*** === **``git push -u origin Charles``**
- ***Mobile testing*** === **``git push -u origin Mobile_testing``**

3. ***В ветке Bug Reports сделать текстовый документ со структурой баг репорта*** === **``git checkout Bug_Reports => vim bug_report_1``**
4. ***Запушить структуру багрепорта на внешний репозиторий*** === **``git add . => git commit -m "Add bug_report_1" => git push``**
5. ***Вмержить ветку Bag Reports в Main*** === **``git checkout main => git merge Bug_Reports``**
6. ***Запушить main на внешний репозиторий.*** === **``"Compare & pull request" https://github.com/victut/Group_29/tree/main => "Create pull request" => "Merge pull request" => "Confirm merge"``**
7. ***В ветке CheckLists набросать структуру чек листа.*** === **``git checkout CheckLists => vim checklist_1``**
8. ***Запушить структуру на внешний репозиторий*** === **``git add . => git commit -m "Add checklist_1" => git push``**
9. ***На внешнем репозитории сделать Pull Request ветки CheckLists в main*** === **``"Compare & pull request" https://github.com/victut/Group_29/tree/main => "Create pull request" => "Merge pull request" => "Confirm merge"``**
10. ***Синхронизировать Внешнюю и Локальную ветки Main*** === **``git checkout main => git pull``**
