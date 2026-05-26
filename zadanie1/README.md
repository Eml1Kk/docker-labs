## Zadanie 1 
docker run -d --name apache -p 8090:80 httpd

bash docker ps

http://localhost:8090

bashdocker logs apache

bashdocker stop apache

bashdocker rm apache

bashdocker rmi httpd