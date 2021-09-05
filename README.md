1. Install docker https://docs.docker.com/desktop/windows/install/
2. Install mysql container: ``docker pull mysql``
3. Start mysql container: ``docker run -p 3307:3306 --name mysql -e MYSQL_ROOT_PASSWORD=root -d mysql``
4. Check running containers: ``docker ps -a``
5. SSH into a running container
6. docker exec -it mysql bash
7. Go into mysql ``mysql -uroot -p -A``
8. Connect Mysqlworkbench (port 3307)

![image-20210905131653685](C:\Users\tramp\AppData\Roaming\Typora\typora-user-images\image-20210905131653685.png)

