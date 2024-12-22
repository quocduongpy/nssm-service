1. add mysql/bin to enviroment to system path
2. create database dir D:\server\mysql\data
3. create config dir: D:\server\mysql\conf
4. run init server : mysqld --defaults-file=D:\server\mysql\conf\my.ini --initialize --console
5. run nssm install mysql-server
   - path: browser to mysqld.exe
   - argruments: --defaults-file=D:\server\mysql\conf\my.ini --console
6. done
