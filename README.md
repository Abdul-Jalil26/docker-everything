# docker-everything

docker helps us to build container. 

what is container?
it's a single package of (software+dependency)

what is docker image?
it's an executable file holds the instruction to build a container


![alt text](image.png)

The relation between docker image and container like the class and object.
inside a class there are objects similarly docker image is a executable file inside it there's docker images.


1) docker run -it ubuntu

it's like virtual machine but it's lightweight


#command---

docker ps 
docker ps -a
docker start 
docker stop
docker run


#Port Binding...

![alt text](docker-port.png)

docker run -d -p 8000:3306 --name mymysql -e MYSQL_ROOT_PASSWORD=yourpassword mysql:latest


host mechine port with docker image port

