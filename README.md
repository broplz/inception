# inception
docker compose project

1. Для того чтобы запустить проект вам понадобится: Docker, Docker-compose

2. Так же для корректной работы нужно будет создать директорию с двумя поддиректориями:
  - /home/${USER}/data/db - для базы данных
  - /home/${USER}/data/wp - для данных wordpress

3. C помощью Makefile в корне проекта необходимо собрать образы командой "make all" или просто "make"

4. Для проверки работают ли сервисы правильно необходимо ввести "make ps"

5. Для проверки работоспособности в браузере нужно перейти по адресу "hcherrie.42.fr" или "localhost" или "127.0.0.1"
