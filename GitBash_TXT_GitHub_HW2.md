TXT
 1. ������� ������� ����������� c ��������� TXT. === https://github.com/victut?tab=repositories -> New -> Repository name "TXT" -> Create repository
 2. ����������� ����������� TXT �� ��������� ���������. === git clone https://github.com/victut/TXT.git
 3. ������ ���������� TXT ������� ���� �new.txt�. === cd TXT/ -> vim new.txt
 4. �������� ���� ��� ���. === git add new.txt
 5. ����������� ����. === git commit -m "Create new.txt"
 6. ��������� ���� �� ������� GitHub �����������. === git push
 7. ��������������� ���������� ����� �new.txt� - �������� ���������� � ���� (���, �������, ���������� �������� ��������, ������� �������� ��������). �� �������� � ������� TXT. === vim new.txt

         1)firstName - Victoria
         2)lastName - Tutaeva
         3)patronymic - Vasilevna
         4)age - 33
         5)pet - 0
         6)future desired salary - 1500$

 8. ��������� ��������� �� ������� �����������. === git commit -am "modified new.txt" -> git push
 9. ������� ���� preferences.txt === vim preferences.txt
 10. � ���� preferences.txt� �������� ���������� � ����� ������������� (������� �����, ������� ������, ������� ���, ������� ����� ����, ������� ������� ������ �� ��������) � ������� TXT.

         1)favorite movie - Lord of the Rings
         2)favorite series - Suits
         3)favorite food - ice cream
         4)favorite season - Spring
         5)country you would like to visit - USA

 11. ������� ���� sklls.txt �������� ���������� � ������� ������� ����� ������� �� ����� � ������� TXT === vim sklls.txt ->

         skills - Git, JavaScript, SQL, API, testing theory

 12. ������� ������ � ���� ������. === git commit -am "modified preferences.txt, sklls.txt" 
 13. ��������� ����� 2 ����� �� ������� �����������. === git push
 14. �� ��� ���������� ������� ���� bug_report.txt. === add file (https://github.com/victut/TXT) -> Create new file -> TXT/bug_report.txt
 15. ������� Commit changes (���������) ��������� �� ��� ����������. === commit new file
 16. �� ��� ���������� �������������� ���� bug_report.txt, �������� ��� ������ � ������� TXT. === "edit this file" https://github.com/victut/TXT/edit/main/bug_report.txt

          1) ID : 1

          2) Summary : When clicking on the 'Update' button, the product is not added to the minicart from the product page

          3) Step to reproduce : Open the website page: http://astrio-spa.dev-mage3.com/venia-accessories.html Open the product card. Add item to cart

          4) Result : A pop-up window does NOT appear stating that the item has been added to the cart. The cart counter has NOT increased by the number of items added to the cart. There is no item in the cart

          5) Expected result : A pop-up window appears stating that the product has been added to the cart. The cart counter has increased by the number of items added to the cart. The item has been added to the cart

          6) Reproducibility : Not on all product pages
          
7) Severity : Critical
          
8) Priority : High(1)

          9) Environment : Windows 7 x64 Google Chrome Version 96.0.4664.45, (64 bit)

 17. ������� Commit changes (���������) ��������� �� ��� ����������. === Commit changes
 18. ���������������� ������� � ��������� ����������� TXT === git pull