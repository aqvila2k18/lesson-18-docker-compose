Заняття 18 - ДЗ 14. Docker Secrets

Для запуска необходимо скачать все 3 файла в одну директорию

docker swarm init

docker stack deploy -c docker-compose.yml wordpress

Пароли храняться в файликах db-password.txt и mysql-root-password.txt . Файлы должны храниться в той же директории что и docker-compose.yml .
