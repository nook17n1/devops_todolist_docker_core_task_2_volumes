How to run MySQL container with a volume attached:
docker run -d -v mysqldata:/var/lib/mysql -p 3306:3306 --name mysql-container mysql-local:1.0.0

How to run an App container which will connect to a MySQL db container:
docker run -p 8000:8000 todoapp:2.0.0

Link to my personal docker hub repository with an todoapp image:
https://hub.docker.com/repository/docker/nook17n1/todoapp/tags/2.0.0/sha256-e0a110231dccf99990f453350f7c97821e85a54a9caeefdc9d62db2b69c79c3d

How to access the application via a browser:
http://127.0.0.1:8080/