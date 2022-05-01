1) ***Посмотреть где я***           ===  **`pwd`**
2) ***Создать папку***              ===  **`mkdir folder`**
3) ***Зайти в папку***              ===  **`cd folder`**
4) ***Создать 3 папки***            ===  **`mkdir folder1 folder2 folder3`**
5) ***Зайти в любую папку***        ===  **`cd folder1`**
6) ***Создать 5 файлов (3 txt, 2 json)*** ===  **`touch file1.txt file2.txt file3.txt file4.js file5.js`**
7) ***Создать 3 папки***            ===  **`mkdir test1 test2 test3`**
8) ***Вывести список содержимого папки*** ===  **`ls -la`**
9) ***Открыть любой txt файл***     ===  **`cat file1.txt`**
10) ***Написать туда что-нибудь,
любой текст***                      ===  **`cat >> file1.txt`**
11) ***Сохранить и выйти***         ===  **`Enter и ctrl+C`**
12) ***Выйти из папки на уровень выше*** ===  **`cd ..`**
13) ***Переместить любые 2 файла, 
которые вы создали, в любую другую 
папку***                            ===  **`mv folder1/{file1.txt,file2.txt} folder2`** 
14) ***Скопировать любые 2 файла, 
которые вы создали,
 в любую другую папку***            ===  **`cp folder2/{file1.txt,file2.txt} folder1`**
15) ***Найти файл по имени***       ===  **`find . -type f -name file1.txt`**                               
16) ***Просмотреть содержимое
 в реальном времени (команда grep)
 изучите как она работает***        ===  **`tail -f file1.txt`** 
17) ***Вывести несколько первых строк
 из текстового файла***             ===  **`head -n file1.txt`**
18) ***Вывести несколько последних 
строк из текстового файла***        ===  **`tail -n2 file1.txt`**
19) ***Просмотреть содержимое длинного   
 файла (команда less) изучите 
как она работает***                 ===  **`less file.txt`**
20) ***Bывести дату и время***      ===  **`date`**

***

***Задание \*:***
1) ***Отправить http запрос на сервер.*** **`http://162.55.220.72:5005/terminal-hw-request`**

***curl*** **`"http://162.55.220.72:5005/get_method?name=Vi&age=33"
"result":["Vi","33"]`**

curl "http://162.55.220.72:5005/get_method?name=Vi&age=33"
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100    12  100    12    0     0    106      0 --:--:-- --:--:-- --:--:--   108 **`["Vi","33"]`**


2) ***Написать скрипт который выполнит автоматически пункты 3, 4, 5, 6, 7, 8, 13:***

    		touch myscript.txt
    		vim myscript.txt
    		#!/bin/bash
    		cd folder
    		mkdir folder1 folder2 folder
    		cd folder1
    		touch file1.txt file2.txt file3.txt file4.js file5.js
    		mkdir test1 test2 test3
    		ls -la
    		cd ..
    		mv folder1/{file1.txt,file2.txt} folder2
    		chmod +x ./myscript.txt
    		./myscript.txt
                   

