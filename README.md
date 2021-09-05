1. Install docker https://docs.docker.com/desktop/windows/install/
2. Install mysql container: ``docker pull mysql``
3. Start mysql container: ``docker run -p 3307:3306 --name mysql -e MYSQL_ROOT_PASSWORD=root -d mysql``
4. Check running containers: ``docker ps -a``
5. SSH into a running container
6. docker exec -it mysql bash
7. Go into mysql ``mysql -uroot -p -A``
8. Connect Mysqlworkbench (port 3307)

![image](https://user-images.githubusercontent.com/34885915/132124977-aab1fa26-18df-402e-87bb-4f2dee4c6779.png)

https://www.youtube.com/watch?v=X8W5Xq9e2Os
