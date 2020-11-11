# Dockerize with mysql database

* Rename umls-example.env to umls.env
* Add UMLS credentials to umls.env
* Change the port and the image name in docker-compose.yml if required
```
docker-compose up db
```
* This will create database
* Wait till database is created. This may take few minutes.
* Ctrl-C to stop containers
```
docker-compose up
```
* Yes, again.
* Access it at the port specified in docker-compose.yml
* You can delete the builder image which is approximately 17 GB
* The final ctakes container is below 2 GB
