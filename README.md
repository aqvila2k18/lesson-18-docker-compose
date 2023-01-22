Заняття 18 - ДЗ 14. Docker Secrets.
Второй вариант, когда пароли хранятся не в файле, а в Docker secret

docker swarm init

printf "A-secret-root-password" | docker secret create mysql-root-password - 

printf "A-secret-db-password" | docker secret create db-password - 

docker stack deploy -c docker-compose.yml wordpress
