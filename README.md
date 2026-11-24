# web-ci

Навчальний проєкт: статичний сайт у контейнері nginx.

Збирання і запуск:

    docker build -t web-ci .

    docker run -d -p 8080:80 web-ci
