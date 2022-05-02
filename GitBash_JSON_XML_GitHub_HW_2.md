��� ��������� �� �� ��������.
 1. �������� ���������� ���� ��� � ������ �� �� Terminal.
 2. �������� ���������� � ���� ����.
 3. �� ������ ������� �������� - �������� ������� � GitBash

JSON

 4. ������� ������� ����������� c ��������� JSON. === https://github.com/victut?tab=repositories -> New -> Repository name "JSON" -> Create repository
 5. ����������� ����������� JSON �� ��������� ���������. === git clone https://github.com/victut/JSON.git
 6. ������ ���������� JSON ������� ���� �new.json�. === cd JSON/ -> vim new.json  
 7. �������� ���� ��� ���. === git add new.json
 8. ����������� ����. === git commit -m "Create new.json"
 9. ��������� ���� �� ������� GitHub �����������. === git push
 10. ��������������� ���������� ����� �new.json� - �������� ���������� � ���� (���, �������, ���������� �������� ��������, ������� �������� ��������). �� �������� � ������� JSON. === vim new.json
-> {
        "firstName" : "Victoria",
        "lastName": "Tutaeva",
        "patronymic" : "Vasilevna",
        "age" : 33,
        "pet" : 0,
        "futureDesiredSalary" : "1500$"
}

 11. ��������� ��������� �� ������� �����������. === git commit -am "modified new.json" -> git push
 12. ������� ���� preferences.json === vim preferences.json 
 13. � ���� preferences.json �������� ���������� � ����� ������������� (������� �����, ������� ������, ������� ���, ������� ����� ����, ������� ������� ������ �� ��������) � ������� JSON. ===
{
        "favoriteMovie" : "Lord of the Rings",
        "favoriteSeries" : "Suits",
        "favoriteFood" : "ice cream",
        "favoriteSeason" : "Spring",
        "countryYouWouldLikeToVisit" : "USA"
}

 14. ������� ���� sklls.json �������� ���������� � ������� ������� ����� ������� �� ����� � ������� JSON === vim sklls.json ->
{
        "skills" : ["Git", "JavaScript", "SQL", "API", "testing theory" ]
}
 15. ��������� ����� 2 ����� �� ������� �����������. === git add . -> git commit -m "Created preferences.json, sklls.json" ->  git push
 16. �� ��� ���������� ������� ���� bug_report.json. === add file (https://github.com/victut/JSON) -> Create new file -> JSON/bug_report.json
 17. ������� Commit changes (���������) ��������� �� ��� ����������. === commit new file
 18. �� ��� ���������� �������������� ���� bug_report.json, �������� ��� ������ � ������� JSON. === "edit this file" https://github.com/victut/JSON/blob/main/bug_report.json -> 
{
  
        "ID" : 1,
  
        "Summary" : "When clicking on the 'Update' button, the product is not added to the minicart from the product page" ,
  
        "StepToReproduce" : "Open the website page: http://astrio-spa.dev-mage3.com/venia-accessories.html Open the product card. Add item to cart",
  
        "Result" : "A pop-up window does NOT appear stating that the item has been added to the cart. The cart counter has NOT increased by the number of items added to the cart. There is no item in the cart",
  
	"ExpectedResult" : "A pop-up window appears stating that the product has been added to the cart. The cart counter has increased by the number of items added to the cart. The item has been added to the cart",
  
	"Reproducibility" : "Not on all product pages",
  
	"Severity" : "Critical",
  
	"Priority" : "High(1)",
  
	"Environment" : "Windows 7 x64 Google Chrome Version 96.0.4664.45, (64 bit)"

}
 19. ������� Commit changes (���������) ��������� �� ��� ����������. === Commit changes
 20. ���������������� ������� � ��������� ����������� JS === git pull

XML

 21. ������� ������� ����������� c ��������� XML. === https://github.com/victut?tab=repositories -> New -> Repository name "XML" -> Create repository
 22. ����������� ����������� XML �� ��������� ���������. === git clone https://github.com/victut/XML.git
 23. ������ ���������� XML ������� ���� �new.xml�. === cd XML/ ->  vim new.xml
 24. �������� ���� ��� ���. === git add new.xml
 25. ����������� ����. ===  git commit -m "Created new.xml"
 26. ��������� ���� �� ������� GitHub �����������. === git push
 27. ��������������� ���������� ����� �new.xml� - �������� ���������� � ���� (���, �������, ���������� �������� ��������, ������� �������� ��������). �� �������� � ������� XML. === vim new.xml

<?xml version="1.0"?>
<firstName>Victoria</firstName>
<lastName>Tutaeva</lastName>
<patronymic>Vasilevna</patronymic>
<age>33</age>
<pet>0</pet>
<futureDesiredSalary>1500$</futureDesiredSalary>

 28. ��������� ��������� �� ������� �����������. === git commit -am "modified new.xml" -> git push
 29. ������� ���� preferences.xml === vim preferences.xml
 30. � ���� preferences.xml �������� ���������� � ����� ������������� (������� �����, ������� ������, ������� ���, ������� ����� ����, ������� ������� ������ �� ��������) � ������� XML. ===

<?xml version="1.0"?>
<favoriteMovie>Lord of the Rings</favoriteMovie>
<favoriteSeries>Suits</favoriteSeries>
<favoriteFood>ice cream</favoriteFood>
<favoriteSeason>Spring</favoriteSeason>
<countryYouWouldLikeToVisit>USA</countryYouWouldLikeToVisit>


 31. ������� ���� sklls.xml �������� ���������� � ������� ������� ����� ������� �� ����� � ������� XML === vim sklls.xml -> 

<?xml version="1.0"?>
<skills>Git, JavaScript, SQL, API, testing theory</skills>

 32. ������� ������ � ���� ������. === git commit -am "modified prefereces.xml, sklls.xml"
 33. ��������� ����� 2 ����� �� ������� �����������. === git push
 34. �� ��� ���������� ������� ���� bug_report.xml. === add file (https://github.com/victut/XML) -> Create new file -> XML/bug_report.xml
 35. ������� Commit changes (���������) ��������� �� ��� ����������. === commit new file
 36. �� ��� ���������� �������������� ���� bug_report.xml, �������� ��� ������ � ������� XML. === "edit this file" https://github.com/victut/XML/edit/main/bug_report.xml ->

<?xml version="1.0"?>

<ID>1</ID>

<Summary>When clicking on the 'Update' button, the product is not added to the minicart from the product page</Summary>

<StepToReproduce>Open the website page: http://astrio-spa.dev-mage3.com/venia-accessories.html Open the product card. Add item to cart</StepToReproduce>

<Result>A pop-up window does NOT appear stating that the item has been added to the cart. The cart counter has NOT increased by the number of items added to the cart. 

	There is no item in the cart</Result>

<ExpectedResult>A pop-up window appears stating that the product has been added to the cart. The cart counter has increased by the number of items added to the cart.
 
	The item has been added to the cart</ExpectedResult>

<Reproducibility>Not on all product pages</Reproducibility>

<Severity>Critical</Severity>

<Priority>High(1)</Priority>

<Environment>Windows 7 x64 Google Chrome Version 96.0.4664.45, (64 bit)</Environment>


 37. ������� Commit changes (���������) ��������� �� ��� ����������. === Commit changes
 38. ���������������� ������� � ��������� ����������� XML === git pull


