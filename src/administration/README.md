� ���� ����� ����� open source  �������� ������� �� node. ������� ��� ������ ����� �������� � ��� ���� ���������� node.js?�.��� �� ��� ������ ���� �� ����� ����������� � �������������� node ���������� �� ����� ���������� c Windows, ������ ��� ������ ��� �� ������?
�� ����������� ����� ���� ������������ ��� Windows � Mac OS, ��� �� ���� ��������� ��� Linux �������������. �� ������ ��������� �� Windows, �� ����� ������� �������� ��� ������ ��.
[Node.js](https://nodejs.org/en/download/)
�������� ���������� ������� �� ������ ������� � ����������. �� ����� ������������ 64-bit Windows Installer. ��� ������� ������������ ����� ������ �� ����� ������������.
![�������� ��������](http://webupblog.ru/wp-content/uploads/2015/06/Screenshot_1.png)
����� �������� �����, ������� �� ���� � ��������� ������ ���������.
![Setup](http://webupblog.ru/wp-content/uploads/2015/06/Screenshot_2.png)
�������� �� �����  � ���� ���� ������ �������� ���������.
![Setup2](http://webupblog.ru/wp-content/uploads/2015/06/Screenshot_3.png)

����� ��������� node.js ���������, ��������� ��� ������� ������� �������, ��� ��������� node ���������� � ������ ����������. �� �������� ������� ���������� ��� ������������.

�������� ����� ��� ������ ����������. � ������ ����� project �� ����� C:/ ������ ������� ������ ��� ������� myapp.
![project](http://webupblog.ru/wp-content/uploads/2015/06/Screenshot_5.png)
������ �������� myapp �������� ���� hello.js � �������� � ��� ��������� ���:
var http = require('http');

http.createServer(function (request, response) {
  response.writeHead(200, {'Content-Type': 'text/plain'});
  response.end('Hello World\n');
}).listen(3000);

console.log('Server running at http://localhost:3000/');

�������������� ���� ��� ������ ���������������� ������ ���� � ������������ ����� node, ������� ������� HTTP web server �� ����� ����������.

������ �� ������ ��������� ���� ������ Node.js ����������.

�������� Node.js ��������� ������ ��� ��������� � ���� ���� Windows, ��� �������������� �������.
![command](http://webupblog.ru/wp-content/uploads/2015/06/Screenshot_6.png)
��������� ������ node ���������� ��������� (CLI). � ������� ��������� ������ ������� � ������� myapp

cd C:\project\myapp

����� ������� �������� ���� hello.js. ����� �������

node hello.js
���� ��� ������ �������, �� ������� ��������� ��������� � ��������� ������.
![hello](http://webupblog.ru/wp-content/uploads/2015/06/Screenshot_7.png)
� ����� ������� �������� ������� URl:
http://localhost:3000/
�� ������ ������� ��������� Hello word � ���� ��������, ������� �������� ��� ��� �������� �������.
![localhost](http://webupblog.ru/wp-content/uploads/2015/06/Screenshot_8.png)