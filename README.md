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
