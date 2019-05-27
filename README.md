# docker-mysql
Simple mysql docker container for test purposes.
1) Clone the repo.
2) Navigate into the folder and run docker-compose up --build
3) docker exec -it docker-mysql_db_1 bash to access the container
4) mysql -uroot -psecret to access mysql. credentials can be changed in the docker file.
5) Create your schemas
