Simple NewsPaper Project using Django

Language: Python 3.8.5

Framework: Djano 3.3.1

How to run:

cd into newspaper-app directory then:

docker-compose up -d

docker-compose exec web python manage.py makemigrations

docker-compose exec web python manage.py migrate

