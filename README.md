# notes
coforge

https://dev.mysql.com/downloads/file/?id=531676
******** MySQL(Portable) Installation Steps ************

1) Visit https://dev.mysql.com/downloads/file/?id=531676 

2) Extract it and paste to c: drive

3) Go to C:\mysql-9.0.1-winx64\bin in command Prompt
issue command
```
	mysqld --initialize --console
	mysqld --console
```
4)Open one more cmd prompt - C:\mysql-9.0.1-winx64\bin 
```
	mysql -u root -p
```
Enter the temporary password from point 3. 
The root is default MySQL user name. 

Then type: 
```
mysql> ALTER USER 'root'@'localhost' IDENTIFIED BY 'MyPass123';
```

5) Daily.
go to C:\mysql-9.0.1-winx64\bin
```
	mysqld --console
```
another cmd
```
	mysql -u root -p
```
```
> select now(),version();
```
# Node and Angular
https://github.com/gsrajudupi-hash/nodejs.git
put this in c after extracting 


https://github.com/gsrajudupi-hash/angular-app.git
put this in training

open vs code 
type cmd on terminal if it showing PS
type set path=C:\node-v20.18.0-win-x64
npm -v
node -v 
ng serve to start angular project
