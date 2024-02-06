
сбора контейнера sudo docker build -t my_container .

запуск контейнера sudo docker run -v /home/user/Desktop/data:/app/data --gpus all -p 8888:8888 my_container