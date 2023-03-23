# Branch

# Command to create Docker Network
Command to create Docker Network
```
$ docker network create some-network
```
# Command to run a latest MySQL docker image with name of db and root password=my-secret-password
Command to run latest MySQL Docker image with name db and root password=my-secret-password
```
$ docker run --name db -e MYSQL_ROOT_PASSWORD=my-secret-password -d mysql:latest
```
# Command to run phpmyadmin docker image on port 80
Command to run phpmyadmin docker image on port 80
```
docker run \
	-p 8080:80 \
	-e PMA_HOST=mysql \
	-d phpmyadmin/phpmyadmin/
```