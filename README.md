1) docker swarm init
2) docker secret create db-password pass.txt
3) docker-compose up --build -d
4) docker-compose exec backend /usr/local/bin/python manage.py migrate