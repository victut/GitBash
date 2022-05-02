TXT
 1. Создать внешний репозиторий c названием TXT. === https://github.com/victut?tab=repositories -> New -> Repository name "TXT" -> Create repository
 2. Клонировать репозиторий TXT на локальный компьютер. === git clone https://github.com/victut/TXT.git
 3. Внутри локального TXT создать файл “new.txt”. === cd TXT/ -> vim new.txt
 4. Добавить файл под гит. === git add new.txt
 5. Закоммитить файл. === git commit -m "Create new.txt"
 6. Отправить файл на внешний GitHub репозиторий. === git push
 7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT. === vim new.txt

         1)firstName - Victoria
         2)lastName - Tutaeva
         3)patronymic - Vasilevna
         4)age - 33
         5)pet - 0
         6)future desired salary - 1500$

 8. Отправить изменения на внешний репозиторий. === git commit -am "modified new.txt" -> git push
 9. Создать файл preferences.txt === vim preferences.txt
 10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.

         1)favorite movie - Lord of the Rings
         2)favorite series - Suits
         3)favorite food - ice cream
         4)favorite season - Spring
         5)country you would like to visit - USA

 11. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT === vim sklls.txt ->

         skills - Git, JavaScript, SQL, API, testing theory

 12. Сделать коммит в одну строку. === git commit -am "modified preferences.txt, sklls.txt" 
 13. Отправить сразу 2 файла на внешний репозиторий. === git push
 14. На веб интерфейсе создать файл bug_report.txt. === add file (https://github.com/victut/TXT) -> Create new file -> TXT/bug_report.txt
 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе. === commit new file
 16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT. === "edit this file" https://github.com/victut/TXT/edit/main/bug_report.txt

          1) ID : 1

          2) Summary : When clicking on the 'Update' button, the product is not added to the minicart from the product page

          3) Step to reproduce : Open the website page: http://astrio-spa.dev-mage3.com/venia-accessories.html Open the product card. Add item to cart

          4) Result : A pop-up window does NOT appear stating that the item has been added to the cart. The cart counter has NOT increased by the number of items added to the cart. There is no item in the cart

          5) Expected result : A pop-up window appears stating that the product has been added to the cart. The cart counter has increased by the number of items added to the cart. The item has been added to the cart

          6) Reproducibility : Not on all product pages
          
7) Severity : Critical
          
8) Priority : High(1)

          9) Environment : Windows 7 x64 Google Chrome Version 96.0.4664.45, (64 bit)

 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе. === Commit changes
 18. Синхронизировать внешний и локальный репозиторий TXT === git pull