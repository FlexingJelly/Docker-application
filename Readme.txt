Работу сдавал студент Чукаев из группы 20ПМИ-1
1) Приведена программа из лабораторной работы hello.py и docker-файл к ней
   Образ собирается и запускается стандартными командами docker build -t image_name . и docker run -it image_name
2) Образ запушен на Dockerhub https://hub.docker.com/repository/docker/ivanchukaev/devops/general
3) Github actions https://github.com/FlexingJelly/Docker-application/blob/main/.github/workflows/docker-image.yml
   настроены для автоматического билда и пуша в Dockerhub при push-е и открытии pull request в ветке main Github
