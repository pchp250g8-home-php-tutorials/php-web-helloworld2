HelloWorld2. PHP Tutorials. Simple Input/Output. Html Web Forms. Web Application. 

The application (website) consists of three HTML pages with the file names "index.html," "formget.html," and "form-post.html" and a PHP script with the file name "HelloWorld2.php." All files are encoded in UTF-8.
The first HTML page with the file name "index.html" is the start page of the web application (site).
Consists of the following elements:
  1. Web page title "Methods of Forms".
  2. Paragraph with the value "Input Your Name".
  3. A paragraph with a hyperlink to a web form file (web page) with the "GET" data submission method.
  4. A paragraph with a hyperlink to a web form file (web page) with the "POST" data submission method.
The second HTML page with the file name "form-get.html" is a web form with the page title "Input Your Name. Form Get Method" and the data sending method "Get" to a PHP script with the file name "HelloWorld2.php".
Consists of the following elements:
  1. An inscription with the text "Input your name" and dimensions of 120 pixels wide and 30 pixels high.
  2. A text field with dimensions of 120 pixels wide and 30 pixels high and an element name of "TextEdit1".
  3. A button of the "Send data to server" type with dimensions of 120 pixels wide and 30 pixels high and the element name "button1".
  There is a caption on it with the text "Send data to the server".
  4. A "Reset data" button with dimensions 120 pixels wide and 30 pixels high and element name "button2".
     There is a sign on it that says "Data reset".
All elements are placed in a table with two columns and two rows.
The third HTML page with the file name "form-post.html" is a web form with the page title "Input Your Name. Form Post Method" and the data sending method "POST" to a PHP script with the file name "HelloWorld2.php".
Consists of the following elements:
  1. An inscription with the text "Input your name" and dimensions of 120 pixels wide and 30 pixels high.
  2. A text field with dimensions of 120 pixels wide and 30 pixels high and an element name of "TextEdit1".
  Consists of the following elements:
  3. A button of the "Send data to server" type with dimensions of 120 pixels wide and 30 pixels high and the element name "button1".
  There is a caption on it with the text "Send data to the server".
  4. A "Reset data" button with dimensions 120 pixels wide and 30 pixels high and element name "button2".
     There is a sign on it that says "Data reset".
All elements are placed in a table with two columns and two rows.
A PHP script with the file name "HelloWorld2.php" does the following:
  1. Reads data from a web form (either the first or the second).
  2. Displays phrases (each on a new line) on the browser web page: "Hello, World!!!", "PHP Test Web Page!!!"
  3. Generates the phrase "Used Query Method:" plus the value of the server variable "REQUEST_METHOD" and displays it on the browser web page.
  4. Generates the phrase "Hi, " plus the value of the web form text field variable named "TextEdit1" and displays it on the browser web page.
  1. Web page title "Methods of Forms".
  5. Displays a hyperlink to an HTML page with the file name "index.html" (the start page of the web application (site)) and the inscription "Enter Data Again" on the browser web page.

HelloWorld2. Занятия по PHP. Простой Ввод/вывод. HTML Веб Формы. Веб Приложение.
Приложение (веб сайт) состоит из трёх HTML страниц с именами файлов "index.html","form-get.html" и "form-post.html" и скрипта на языке программирования PHP с именем файла "HelloWorld2.php". Все файлы в кодировке "UTF-8".
Первая HTML страница с именем файла "index.html" является стартовой страницей веб приложения (сайта).
Состоит из следующих элементов:
  1. Заголовок веб страницы "Methods of Forms".
  2. Параграф со значением "Input Your Name".
  3. Параграф с гипер-ссылкой на файл веб формы (веб страницы) с методом отправки данных "GET".
  4. Параграф с гипер-ссылкой на файл веб формы (веб страницы) с методом отправки данных "POST".
Вторая HTML страница с именем файла "form-get.html" является веб формой с заголовком страницы "Input Your Name. Form Get Method" и методом отправки данных "Get" скрипту на языке программирования PHP с именем файла "HelloWorld2.php".
Состоит из следующих элементов:
  1. Надпись с текстом "Input your name" и размерами шириной 120 и высотой 30 пикселей.
  2. Текстовое поле с размерами шириной 120 и высотой 30 пикселей и именем элемента "TextEdit1".
  3. Кнопка типа "Отправить данные на сервер" размерами шириной 120 и высотой 30 пикселей и именем элемента "button1".
     На ней надпись с текстом "Отправить данные на сервер".
  4. Кнопка типа "Сброс данных" размерами шириной 120 и высотой 30 пикселей и именем элемента "button2".
     На ней надпись с текстом "Сброс данных".
Все элемнты размещены в таблице с двумя столбцами и двумя строками.
Третья HTML страница с именем файла "form-post.html" является веб формой с с заголовком страницы "Input Your Name. Form Post Method" и методом отправки данных "POST" скрипту на языке программирования PHP с именем файла "HelloWorld2.php".
Состоит из следующих элементов:
  1. Надпись с текстом "Input your name" и размерами шириной 120 и высотой 30 пикселей.
  2. Текстовое поле с размерами шириной 120 и высотой 30 пикселей и именем элемента "TextEdit1".
  3. Кнопка типа "Отправить данные на сервер" размерами шириной 120 и высотой 30 пикселей и именем элемента "button1".
     На ней надпись с текстом "Отправить данные на сервер".
  4. Кнопка типа "Сброс данных" размерами шириной 120 и высотой 30 пикселей и именем элемента "button2".
     На ней надпись с текстом "Сброс данных".
Все элемнты размещены в таблице с двумя столбцами и двумя строками.
Скрипт на языке программирования PHP с именем файла "HelloWorld2.php" делает следующее:
  1. Читает данные из веб-формы (либо из первой либо из второй).
  2. Выводит на веб страницу браузера фразы (каждая с новой строки):"Hello, World!!!", "PHP Test Web Page!!!"
  3. Формирует фразу "Used Query Method:" плюс значение серверной переменной "REQUEST_METHOD" и выводит её на веб страницу браузера.
  4. Формирует фразу "Hi, " плюс начение переменной текстового поля веб-формы с именем "TextEdit1" и выводит её на веб страницу браузера.
  5. Выводит на веб страницу браузера гипер-ссылку на HTML страницу с именем файла "index.html" (стартовую страницй веб приложения (сайта)) и надписью "Enter Data Again".
     
