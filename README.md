
# Задание 2

Сборка образа:

* docker build -t my_django:v1 -f django_dockerfile .

Запуск образа:

* docker run -d -p 8000:8000 my_django:v1
